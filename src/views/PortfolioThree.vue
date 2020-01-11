<template>
  <div class="three main-content">
    <div class="left-content slideUp">

      <router-link to="/portfolio/two"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>

      <h1>SEO / SEM </h1>

      <p class="subtxt">No matter if you’re trying to rank for more long-tail keywords or tougher head terms,</p>
      <p class="subtxt">I can provide the guidance you need</p>
        <button><router-link to="/about">Contact me</router-link></button>
    </div>

    <div class="right-content img2">

    </div>
  </div>
</template>

<script>

export default {
  name: 'three'
}
</script>

<style lang="scss" scoped>

  $page_color: #5487a8;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/card.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }





</style>
