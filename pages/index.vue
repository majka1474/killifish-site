<template>
  <div>
    <div class="container">
      <img src="../assets/img/medaka.jpg" alt="メダカの画像" class="medaka" />
      <nuxt-link to="/medaka_detail" class="medaka_detail"
        >メダカの詳細へ</nuxt-link
      >
      <img src="../assets/img/plants.jpg" alt="水草の画像" class="plants" />
      <nuxt-link to="/plants_detail" class="plants_detail"
        >水草の詳細へ</nuxt-link
      >
      <img src="../assets/img/ikusei.jpg" alt="育成の画像" class="ikusei" />
      <nuxt-link to="/ikusei_detail" class="ikusei_detail"
        >メダカの育て方</nuxt-link
      >
    </div>
    <div class="slider">
      <div id="picture">
        <!-- チェックボックス -->
        <input type="radio" name="picture" id="pic1" checked />
        <input type="radio" name="picture" id="pic2" />
        <input type="radio" name="picture" id="pic3" />
        <input type="radio" name="picture" id="pic4" />
        <div id="bg-pic">
          <div class="inside">
            <nuxt-link to="/esa"><div class="pic pic_1"></div></nuxt-link>
            <nuxt-link to="/"><div class="pic pic_2"></div></nuxt-link>
            <nuxt-link to="/"><div class="pic pic_3"></div></nuxt-link>
            <nuxt-link to="/"><div class="pic pic_4"></div></nuxt-link>
          </div>
        </div>
        <!-- スライダーのコントロールボタンを指定 -->
        <div id="slide-controls">
          <label for="pic1"></label>
          <label for="pic2"></label>
          <label for="pic3"></label>
          <label for="pic4"></label>
        </div>
        <!-- スライダーのナビゲーションボタン -->
        <div id="slide-buttons">
          <label for="pic1" id="btn">餌</label>
          <label for="pic2" id="btn">sea</label>
          <label for="pic3" id="btn">scenery</label>
          <label for="pic4" id="btn">road</label>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import scss
import "~/assets/css/container_img.scss";

export default {};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
</style>
