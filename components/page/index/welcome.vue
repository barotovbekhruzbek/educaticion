<template>
  <div class="welcome">
 <div class="welcome__body">
    <div class="container">
        <h1>Zamonaviy kasbni
<span>EduCert</span> orqali egallang</h1>
<p>O’z kasbini mutaxassislari tomonidan shakllantirilgan kurslarimiz orqali
o’zingizga mos bilim va salohiyatni qulay holatda o’rganing</p>
<div class="d-flex gap-30">
    <nuxt-link to="/" class="btn rounded">
        Batafsil
    </nuxt-link>
    <nuxt-link to="/" class="btn bordered">
        Barcha kurslarimiz
    </nuxt-link>
</div>
     </div>
     <img src="../../../public/assets/img/main.png" alt="">
 </div>
  </div>
  <partners />
</template>

<script setup>
import partners from './partners.vue'

</script>

<style lang="scss" scoped>
@import '../../../public/assets/css/vars.scss';
@import '../../../public/assets/css/components/welcome.scss'
</style>