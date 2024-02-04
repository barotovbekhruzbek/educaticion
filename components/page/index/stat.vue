<template>
  <div class="stat">
  <div class="item">
    <div class="count">1,320+</div>
    <div class="name">o’quvchilarimiz</div>
  </div>
    <div class="item">
      <div class="count">496,000+</div>
      <div class="name">soat kurslar ko’rilgan</div>
    </div>
    <div class="item">
      <div class="count">19,000+</div>
      <div class="name">Ijobiy izohlar</div>
    </div>
    <div class="item">
      <div class="count">120+</div>
      <div class="name">Kurslarimiz</div>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="scss" scoped>
@import "../../../public/assets/css/vars.scss";
.stat{
  background: #FEFBF4;
  display: flex;
  justify-content: center;
  gap: 130px;
  padding: 56px 0px;
  .item {
    text-align: center;
    .count {
      font-size: 35px;
      color: $blue;
      margin-bottom: 8px;
      font-weight: bolder ;
    }
    .name {
      color: $violet;

    }
  }
}
</style>