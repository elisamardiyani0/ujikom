<template>
  <nav class="navbar navbar-expand-lg bg-secondary sticky-top" style="width: 100%">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"> <img src="~assets/img/logo.png" alt="logo" width="70" /> </a>
      <h3 class="text-white">SMK Negri 4 Tasikmalaya</h3>
      <div class="justify-content-end collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <nuxt-link to="/">
            <li class="nav-item">
              <h4 class="nav-link active" aria-current="page" href="#">Beranda</h4>
            </li>
          </nuxt-link>
          <nuxt-link to="/profil">
            <li class="nav-item">
              <h4 class="nav-link" href="#">Profil</h4>
            </li>
          </nuxt-link>
          <nuxt-link to="/galeri">
            <li class="nav-item">
              <a class="nav-link" href="#">Galeri</a>
            </li>
          </nuxt-link>
          <nuxt-link to="/eskul">
            <li class="nav-item">
              <a class="nav-link" href="#">Ekstrakurikuler</a>
            </li>
          </nuxt-link>
          <nuxt-link to="/kontak">
            <li class="nav-item">
              <a class="nav-link" href="#">Kontak</a>
            </li>
          </nuxt-link>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
a {
  text-decoration: none;
}
</style>
