<template>
    <div v-if="videos.length === 0">Loading Instagram videos...</div>
    <div v-else>
      <div v-for="video in videos" :key="video.id" class="col">
        <div class="instagram-feed">
          <video controls :src="video.video_url" :poster="getProxyUrl(video.thumbnail)" class="instagram-media"></video>
          <p>{{ video.caption }}</p>
        </div>
      </div>
    </div> 
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      videos: [],
    };
  },
  async mounted() {
    await this.fetchInstagramVideos();
  },
  methods: {
    async fetchInstagramVideos() {
      try {
        const response = await axios.get("http://127.0.0.1:8000/api/instagram-feed");
        this.videos = response.data;
      } catch (error) {
        console.error("Error fetching Instagram videos:", error);
      }
    },
    getProxyUrl(url) {
      return `http://127.0.0.1:8000/api/proxy-image?url=${encodeURIComponent(url)}`;
    }
  },
};
</script>

<style scoped>

</style>
