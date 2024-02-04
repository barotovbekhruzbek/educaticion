<template>
   <div class="card">
    <NuxtLink to="/" class="card__img">
        <div class="badge top">TOP</div>
        <img src="/assets/img/cours-card/1.png" alt="">
    </NuxtLink>
    <div class="card__body">
        <div class="rating">
             <div class="avarage">4.5</div>
             <div class="stars">
                <img src="/assets/img/cours-card/stars.svg" alt="">
                <img src="/assets/img/cours-card/stars.svg" alt="">
                <img src="/assets/img/cours-card/stars.svg" alt="">
                <img src="/assets/img/cours-card/stars.svg" alt="">
                <img src="/assets/img/cours-card/stars.svg" alt="">
             </div>
             <div class="all">(1999)</div>
        </div>
        <NuxtLink to="/" class="card__title"> 
            Zero dan Expertgacha Intensiv Python backend dasturlash
        </NuxtLink>
        <div class="level">
            <div class="item">
                <img src="/assets/img/cours-card/document.svg" alt="">
                16 dars
            </div>
            <div class="item">
                <img src="/assets/img/cours-card/wall-clock.svg" alt="">
                +4 soat
            </div>
            <div class="item">
                <img src="/assets/img/cours-card/bar-chart.svg" alt="">
                Boshlang`ich
            </div>
        </div>
        <div class="bottom">
            <div class="author">
                <img src="/assets/img/cours-card/author.png" alt="">
                Sardor Komilov
            </div>
            <div class="price">
                700 ming so`m
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
@import url("../../public/assets/css/components/card.scss");

</style>