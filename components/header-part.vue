<template>
<header>
  <nuxt-link to="/" class="logo">
    <img src="assets/img/logo.svg" alt="">
  </nuxt-link>
  <div class="links">
    <nuxt-link to="/">Bosh sahifa</nuxt-link>
    <nuxt-link to="/">Biz haqimizda</nuxt-link>
    <nuxt-link to="/">Kurslar</nuxt-link>
    <nuxt-link to="/">Hamkorlar</nuxt-link>
    <nuxt-link to="/">Mijozlar</nuxt-link>
    <nuxt-link to="/">Yangiliklar</nuxt-link>
    <nuxt-link to="/">Aloqa</nuxt-link>

  </div>
  <div class="search">
    <button>
      <img src="assets/img/search-icon.svg" alt="">
    </button>

  </div>
  <div class="lang">
    <div class="current">
      <img src="assets/img/global-search.svg" alt="">
      O`zbekcha
    </div>
    <ul class="list">
      <li>
        Русский
      </li>
      <li>
        English
      </li>
    </ul>
  </div>
  <nuxt-link to="/" class="login">Kirish</nuxt-link>
</header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
  @import '../public/assets/css/header.scss';
</style>