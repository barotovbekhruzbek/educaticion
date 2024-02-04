<template>
  <div class="pluslist">
    <div class="container">
        <div class="title text-center"> 
            EduCert bilan zamonaviy kasbga ega bo’ing
        </div>
        <div class="row">
          <div class="col-6" v-for="card of list" :key="card.id">
            <div class="pluscard">
              <div :class=" `plusimg ${card.color}`">
                <img :src="card.img" alt="">
              </div>
              <div class="plustitle">
                {{ card.title }}
              </div>
              <p> {{ card.text }}</p>
            </div>
          </div>
        </div>
    </div>
  </div>
</template>

<script setup>
  const list = ref([
    {
      title: 'Mutaxassislar bilan o’rgan',
      text: 'Barcha kurslarni o’z ishining mutaxassislari tomonidan olib boriladi',
      img : "assets/img/plus-card1.svg",
      color: "spec"
    },
    {
      title: 'Xoxlagan joyda o’rgan',
      text: 'O’quv platformamiz orqali istalgan hududda o’rganishingiz mumkin',
      img : "assets/img/plus-card2.svg",
      color: "place"
    },
    {
      title: 'Qulay o’quv jarayon',
      text: "O’quv rejalari har bir o’rganuvchi uchun individual holatda shakllantiriladi",
      img : "assets/img/plus-card3.svg",
      color: "learn"
    },
    {
      title: 'Akkreditatsiyali sertifikat',
      text: "Kurs muvaffaqiyatli tugatgan o’quvchilarimi akkreditatsiyadan o’rgan serfikatga ega bo’ladi",
      img : "assets/img/plus-card4.svg",
      color: "learn"
    },
  ])
</script>

<style lang="scss" scoped>
@import "../../../public/assets/css/components/pluslist.scss";
</style>