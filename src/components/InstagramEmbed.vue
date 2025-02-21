<template>
    <div v-if="loading" class="text-center">Loading Instagram videos...</div>
    <div v-else-if="errorMessage" class="text-red-500">{{ errorMessage }}</div>
    
    <div v-for="(post, index) in instagramFeeds" :key="index" class="col">
      <div class="instagram-feed">
        <blockquote
        class="instagram-media"
        :data-instgrm-permalink="post.embed_url"
        data-instgrm-version="13"
        >
        <a :href="post.embed_url" target="_blank">View Post</a>
      </blockquote>
      </div>
    </div>
</template>

<script setup>
import { ref, onMounted } from "vue";

const instagramFeeds = ref([]);
const loading = ref(true);
const errorMessage = ref(null);

const fetchInstagramFeeds = async () => {
  try {
    const response = await fetch("http://127.0.0.1:8000/api/instagram-embed");
    if (!response.ok) throw new Error("Failed to fetch Instagram feed");
    instagramFeeds.value = await response.json();
  } catch (error) {
    console.error("Error fetching Instagram feeds:", error);
    errorMessage.value = error.message;
  } finally {
    loading.value = false;
  }
};

onMounted(() => {
  fetchInstagramFeeds().then(() => {
    setTimeout(() => {
      let script = document.createElement("script");
      script.async = true;
      script.src = "https://www.instagram.com/embed.js";
      document.body.appendChild(script);
    }, 100);
  });
});
</script>

<style scoped>

</style>
