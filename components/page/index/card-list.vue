<template>
  <div class="cards-list">
    <div class="title text-center">Eng mashhur kurslarimiz</div>
    <p class="text-center">10, 000+ soatga ega kurslarimiz</p>
    <Swiper
    :modules="[SwiperAutoplay, SwiperEffectCreative]"
    :slides-per-view="3"
    :space-between="35"
    :loop="true"
    :effect="'creative'"
    :autoplay="{
      delay: 8000,
      disableOnInteraction: true,
    }"
    :creative-effect="{
      prev: {
        shadow: false,
        translate: ['-20%', 0, -1],
      },
      next: {
        translate: ['100%', 0, 0],
      },
    }"
  >
    <SwiperSlide v-for="slide in 10" :key="slide">
      <strong>{{ slide }}</strong>
    </SwiperSlide>
  </Swiper>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">

</style>