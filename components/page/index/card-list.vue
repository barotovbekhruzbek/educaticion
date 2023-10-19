<template>
  <div class="cards-list">
    <div class="title text-center">Eng mashhur kurslarimiz</div>
    <p class="text-center">10, 000+ soatga ega kurslarimiz</p>
    <Swiper
    :modules="[SwiperAutoplay, SwiperEffectCreative]"
    :slides-per-view="5"
    :space-between="35"
    :loop="true"

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
      <Card />
    </SwiperSlide>
  </Swiper>
  </div>
</template>

<script setup>
import Card from '~/components/course/Card.vue';
</script>

<style lang="scss">
.cards-list {
    background: #EEF2F6;
    padding: 120px 10px;
    p {
      padding-bottom: 60px;
    }
}
</style>