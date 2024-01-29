<template>
  <div class="cards__list">
    <div class="title text-center">Eng mashhur kurslarimiz</div>
    <p class="text-center">10, 000+ soatga ega kurslarimiz</p>
 <div class="cards__slider">
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
 <NuxtLink to="/" class="more mt-50">Barcha kurslarimiz <img src="../../../public/assets/img/icons/send.svg" alt=""> </NuxtLink>
  </div>
</template>

<script setup>
import Card from '~/components/course/Card.vue';
</script>

<style lang="scss">

.cards {
  &__list {
    display: flex;
    flex-direction: column;
    background: #EEF2F6;
    padding: 120px 10px;
    overflow: hidden;
    p {
      padding-bottom: 60px;
    }
   }
   &__slider {
    margin-left: -150px;
    margin-right: -150px;
   }
  }
  .more {

    background: #033399;
    display: flex;
   justify-content: center;
   align-items: center;
   gap: 13px;
   border-radius: 8px;
   color: #fff;
   font-size: 15px;
   padding: 15px 29px;
   
   margin: 0 auto;
   &:hover {
    background: #E59819;
    transition: 0.3s linear;
   }
  }
  .mt-50 {
    margin-top: 50px;
  }

</style>