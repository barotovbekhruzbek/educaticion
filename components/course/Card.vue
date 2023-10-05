<template>
   <div class="card">
    <NuxtLink to="/" class="card__img">
        <div class="card__badge top">TOP</div>
        <img src="../../public/assets/img/cours-card/1.png" alt="">
    </NuxtLink>
    <div class="card__body">
        <div class="rating">
             <div class="avarage">4.5</div>
             <div class="stars">
                <img src="../../public/assets/img/cours-card/stars.svg" alt="">
                <img src="../../public/assets/img/cours-card/stars.svg" alt="">
                <img src="../../public/assets/img/cours-card/stars.svg" alt="">
                <img src="../../public/assets/img/cours-card/stars.svg" alt="">
                <img src="../../public/assets/img/cours-card/stars.svg" alt="">
             </div>
             <div class="all">(1999)</div>
        </div>
        <NuxtLink to="/" class="card__title"> 
            Zero dan Expertgacha Intensiv Python backend dasturlash
        </NuxtLink>
        <div class="level">
            <div class="item">
                <img src="../../public/assets/img/cours-card/document.svg" alt="">
            </div>
        </div>
    </div>
   </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../../public/assets/css/components/card.scss"
</style>