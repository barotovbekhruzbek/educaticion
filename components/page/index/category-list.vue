<template>
  <div class="category">
    <div class="title text-center">Trenddagi turkumlar</div>
   <div class="container">
    <div class="category-list row">
        <div class="col-6" v-for="item of 8" :key="item.id">
          <div class="category-box">
            <div class="icon">
              <img src="assets/img/icon-catergory/marketing1.png" alt="">
            </div>
            <div class="category-body">
              <div class="category-title">Marketing</div>
              <div class="category-count">573+ kurslar</div>
            </div>
          </div>
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
.category {
  padding: 80px 0px 120px;
}
.category-list {
  display: flex;
  gap: 30px;
}
.category-box {
  width: 300px;
  height: 100px;
  border-radius: 8px;
  border: 1px solid var(--border-1, #EDEDED);
  background: var(--color-5, #FFF);
  display: flex;
  gap: 10px;
  align-items: center;

  .category-body{
    .category-title {
      color: var(--Head---Color, #033399);
      font-size: 17px;
      font-style: normal;
      font-weight: 500;
      line-height: 26px;
      text-transform: capitalize;
    }
    .category-count {
      padding-top: 8px;
      color: var(--Text---Color, #4F547B);

      font-family: GT Walsheim Pro;
      font-size: 13px;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
  }
}

</style>