<template>
  <div class="quota">
    <div class="img">
        <div class="quota-icon">
            <img src="assets/img/quota.svg" alt="">
        </div>
        <img src="/assets/img/quotalist.png" alt="">
    </div>
    <div class="body">
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
        <div class="text">
            “EduCert platformasi orqali biznes va marketing bo’yicha ko’plab foydali bilim va salohiyatlarga ega bo’ldim”
        </div>
        <div class="name">
            Lola Polvonova
        </div>
        <div class="company">“Miracle” do’koni</div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../../public/assets/css/components/quota.scss";
  .rating {
            display: flex;
            text-align: center;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-size: 14px;

            .average {
                color: #E59819;
            }
            .all{
                font-size: 13px;

            }
        }
</style>