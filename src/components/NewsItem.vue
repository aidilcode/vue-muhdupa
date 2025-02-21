<script>
import InstagramItem from '../components/InstagramItem.vue'
import InstagramEmbed from '../components/InstagramEmbed.vue'
export default {
  components: {
    InstagramEmbed
  }
};
</script>

<template>
   <section id="news" class="container mt-5">
        <div class="text-center">
            <button class="btn-jud text-center" data-aos="fade-up">
                <h4 class="h4-jud poppins-medium">Berita Terkini</h4>
            </button>
        </div>
        <nav class="mt-5">
            <div class="nav nav-tabs justify-content-around" id="nav-tab" role="tablist" data-aos="zoom-in">
                <button class="nav-link active" id="nav-news-tab" data-bs-toggle="tab" data-bs-target="#nav-news"
                    type="button" role="tab" aria-controls="nav-news" aria-selected="true">Berita Terbaru</button>
                <button class="nav-link" id="nav-feed-tab" data-bs-toggle="tab" data-bs-target="#nav-feed"
                    type="button" role="tab" aria-controls="nav-feed" aria-selected="false">Feed Instagram</button>
            </div>
        </nav>
        <div class="tab-content" id="nav-tabContent">
            <div class="tab-pane fade show active mt-4 gap-3 justify-content-center " id="nav-news" role="tabpanel" aria-labelledby="nav-news-tab" tabindex="0">
                <div class="row">
                    <div class="col-md-6">
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a session flyer with text and a small photo of a person"
                                        class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/qTaKI0tbB9qZNNfTqiRkHZZsL8YZDOI72Q4eAPQshHXlHeWnA.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Sabtu, 19 Oktober 2024
                                        </p>
                                        <h5 class="card-title">
                                            Sesi Pemantapan TIU Cuma 49rb. Limited Seat! 🔥
                                        </h5>
                                        <p class="card-text">
                                            Cuma 49rb udah bisa ikutan sesi pemantapan TIU buat persiapan tes ...
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a flyer with text '30 Days Try Out Challenge'" class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/uIQBr9byECbPLh4Jt5VoAzej6wHuYb6m7jQy2hsW09KyDv1JA.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Selasa, 03 September 2024
                                        </p>
                                        <h5 class="card-title">
                                            Try Out Exclusive–30 Days Try Out Challenge! Passing Grade Terbaru 2024!
                                        </h5>
                                        <p class="card-text">
                                            Holla everyone 🚀 Yang ditunggu kini hadir lagi,...
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a government building" class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/BxVjUV8iSewefIlx5SP8KBezqTeC7eOe1CvdBXNm123TxDv1JA.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Selasa, 27 Agustus 2024
                                        </p>
                                        <h5 class="card-title">
                                            Formasi CPNS Kejaksaan Agung Tahun 2024! Persyaratan Lengkap Kebutuhan Umum
                                            dan Khusus!
                                        </h5>
                                        <p class="card-text">
                                            Seleksi rekrutmen Calon Pegawai Negeri Sipil (CPNS) tahun 2024 tel...
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a calendar with a plant in the background" class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/5rHRyKRgdCJFPVWvkLGk2AWfFc0fd2GrdDil60ghXa0hHeWnA.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Senin, 09 September 2024
                                        </p>
                                        <h5 class="card-title">
                                            Jadwal Baru Seleksi Pengadaan CPNS 2024! Pendaftaran Ditutup 10 September!
                                        </h5>
                                        <p class="card-text">
                                            Sehubungan dengan terjadinya kendala teknis pada sistem e-meterai ...
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a group of people in uniform" class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/YoOyPbbXjIbVKh1L39bhs2UQudiceilqyw0oAKCpIOnzDv1JA.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Rabu, 28 Agustus 2024
                                        </p>
                                        <h5 class="card-title">
                                            9.070 Formasi CPNS Kementerian Hukum Dan HAM! Penempatan Di 11 Unit Pusat
                                            Dan 33 Kantor Wilayah!
                                        </h5>
                                        <p class="card-text">
                                            Kementerian Hukum Dan Hak Asasi Manusia (Kemenkumham)
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="card-tab" data-aos="zoom-in">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img alt="Image of a document with text" class="img-fluid"
                                        src="https://storage.googleapis.com/a1aa/image/lNMeOKeSbOu43kdVRT7CJgWniF1q5e9JfK5YbFp5de2E9wbdC.jpg" />
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <p class="card-date">
                                            Rabu, 14 Agustus 2024
                                        </p>
                                        <h5 class="card-title">
                                            Resmi Dibuka! Jadwal Lengkap Seleksi CPNS 2024! Catat Tanggalnya!
                                        </h5>
                                        <p class="card-text">
                                            Seleksi Calon Pegawai Negeri Sipil (CPNS) tahun 2024 kembali dibuk...
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        
            <div class="tab-pane fade mt-4" id="nav-feed" role="tabpanel" aria-labelledby="nav-feed-tab" tabindex="0">
                <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-1">
                    <InstagramEmbed />
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped></style>