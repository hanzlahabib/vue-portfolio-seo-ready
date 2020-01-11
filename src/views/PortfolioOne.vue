<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Front End Developer</h1>

      <p> Mission-driven full stack developer with a passion for thoughtful UI design,</p>
      <p class="subtxt"> collaboration, and teaching.</p>

      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>

    <div class="right-content img2">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'one',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>

  $page_color: #625B7E;

  h1 {
    color: $page_color !important;
  }

  .img2 {
     background: url('../assets/phone.jpg') no-repeat;
    background-color: #2b313f;
    background-position: 50%;


    img {
      width: 50%;
    }
  }





</style>
