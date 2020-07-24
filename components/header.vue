<template>
  <header>    
    <nuxt-link to="/" class="title">めだか</nuxt-link>
    <ul>
      <li>
        <nuxt-link to="/sign_up">Sign up</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/sign_in">Sign in</nuxt-link>
      </li>
      <li>
        <button v-on:click="logout" class="logout">logout</button>
      </li>
    </ul>
  </header>
</template>

<script>
// import scss
import "~/assets/css/header.scss"

export default {};
</script>

<style>
* {
  user-select: none;
}

</style>
