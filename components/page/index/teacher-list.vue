<template>
<div class="teachers">
  <div class="container">
    <div class="row">
      <div class="col-6">

      </div>
      <div class="col-18">
        <Swiper
            :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="4"
            :space-between="35"
            :loop="true"

            :autoplay="{
      delay: 8000,
      disableOnInteraction: true,
    }"

        >
          <SwiperSlide v-for="slide in 10" :key="slide">
            <teacher />
          </SwiperSlide>
        </Swiper>

      </div>
    </div>
  </div>
</div>
</template>
<script setup>
import teacher from "../../course/teacher.vue"

</script>
<style lang="scss" scoped>

</style>