<template>
  <div class="quotalist">
    <div class="title">EduCert haqida bitiruvchilarimiz</div>
    <p>1230+ ortiq muvaffaqiyatli yakunlagan o’quvchilarimiz</p>
    <div class="quotaslider">
      <Swiper
          :modules="[SwiperAutoplay, SwiperEffectCreative]"
          :slides-per-view="4"
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
          <quota/>
        </SwiperSlide>
      </Swiper>
    </div>
  </div>
</template>

<script setup>
import quota from "~/components/course/Quota.vue";


</script>

<style lang="scss">
@import "../../../public/assets/css/vars.scss";
.quotalist {
  background: $blue;
  text-align: center;
  color: #fff;
  padding: 120px 0px;
  overflow: hidden;
  .title {
    color: #fff;
    font-weight: bold;
  }
}
.quotaslider {
  margin-left: -350px;
  margin-right: -350px;
}
</style>