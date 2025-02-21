<template>
    <nav class="navbar navbar-expand-lg bg-body sticky-top" id="main-navbar">
        <div class="container align-items-center">
        <div class="d-flex align-items-center">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" 
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <i class=" navbar-toggler-icon"></i>
        </button>
        <p class="d-lg-none d-block m-3 poppins-medium opacity-75">Menu</p>
        </div>
        <a class="navbar-brand" href="#">
            <img src="/img/muhdupa1.png" class="img-fluid" width="60" height="50" alt="">
        </a>
        <div class="collapse navbar-collapse ms-lg-4" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link nav-first poppins-medium" aria-current="page" href="#">Beranda</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link poppins-medium" href="#">Edumu</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link poppins-medium" href="#">Monalisa</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link poppins-medium" href="#">Cyber Muhdupa</a>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center d-none d-lg-flex ">
            <form class="d-flex me-3" role="search">
                <input class=" form-control me-2 rounded-5 border-0 border-bottom search" type="search" placeholder="Search" aria-label="Search">
            </form>
            <div class="d-flex align-items-center">
                <i class="bi bi-alarm-fill me-2 text-secondary"></i>
                <div id="digital-clock" class="fs-6 poppins-regular "></div>
            </div>
        </div>
        </div>
    </nav>
</template>

<script>
export default {
  name: "Test",
  created() {},
  data() {
    return {};
  },
  props: {},
  methods: {},
};
</script>

<style lang="scss" scoped></style>