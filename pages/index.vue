<template>
  <div class="container">
    <img src="../assets/img/medaka.jpg" alt="メダカの画像" class="medaka">
    <nuxt-link to="/medaka_detail" class="medaka_detail">メダカの詳細へ</nuxt-link>
    <img src="../assets/img/plants.jpg" alt="水草の画像" class="plants">
    <nuxt-link to="/plants_detail" class="plants_detail">水草の詳細へ</nuxt-link>
    <img src="../assets/img/ikusei.jpg" alt="育成の画像" class="ikusei">
    <nuxt-link to="/ikusei_detail" class="ikusei_detail">メダカの育て方</nuxt-link>
  </div>
</template>

<script>
// import scss 
import "~/assets/css/container_img.scss"

export default {}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}


</style>
