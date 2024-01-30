<template>
  <div class="partners">
   <div class="container">
    <img src="assets/img/icons/amazon-4.png" alt="">
    <img src="assets/img/icons/amd-logo-1-2.png" alt="">
    <img src="assets/img/icons/cisco-2-1-2.png" alt="">
    <img src="assets/img/icons/dropcam.png" alt="">
    <img src="assets/img/icons/logitech.png" alt="">
    <img src="assets/img/icons/spotify.png" alt="">
   </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '../../../public/assets/css/vars.scss';
.partners {
   background: $grey;
   padding: 39px 0;
   .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
   }
}
</style>