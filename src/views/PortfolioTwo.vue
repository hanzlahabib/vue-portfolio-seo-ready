<template>
  <div class="two main-content">
    <div class="left-content slideUp">

      <router-link to="/portfolio/one"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>


      <h1>UI / UX</h1>
      <p class="subtxt">Web Designer and full-stack developer with interest in immersive computing and emerging technologies.</p>
      <p class="subtxt">Able to take ideas from concept to wireframe to prototype to production</p>

      <router-link to="/portfolio/three"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
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

  $page_color: #48b886;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/ui.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }





</style>
