<template>
  <div class="category">
    <div class="title text-center">Trenddagi turkumlar</div>
   <div class="container">
    <div class="category-list row">
        <div class="col-6" v-for="item of 8">
          <div class="category-box">
            <div class="icon">
              <img src="@/assets/img/icon-catergory/icon1.png" alt="">
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
</style>