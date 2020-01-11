<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Developer</h1>

      <p class="subtxt">Building quality websites and applications with HTML, CSS, and JavaScript.
Web developer and instructor with 4+ years’ of well-rounded experience in MERN development,</p>
      <p class="subtxt"> object-oriented and user-centered design, I love to bring idea to live with the touch of great code.</p>
    </div>

    <div class="right-content img1">
      <button><router-link to="/portfolio/one">Browse Skills</router-link></button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

  .img1 {
    background: url('../assets/home.jpg');
  }

</style>
