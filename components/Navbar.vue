<template>
  <nav
    class="navbar navbar-expand-lg bg-secondary sticky-top"
    style="width: 100%">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="~assets/img/logo.png" alt="logo" width="50" />
      </a>
      <div
        class="justify-content-end collapse navbar-collapse"
        id="navbarNavDropdown">
        <ul class="navbar-nav">
          <nuxt-link to="/">
            <li class="nav-item">
              <div class="nav-link active" aria-current="page" href="#">
                Beranda
              </div>
            </li>
          </nuxt-link>
          <nuxt-link to="/profil">
            <li class="nav-item">
              <div class="nav-link" href="#">Profil</div>
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
