<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About me</h1>
      <p class="subtxt">I design, code, and teach a bunch of other people to do the same.</p>
      <a href="http://hanzla.com/#contact">Send Us your Query</a>
      <button><router-link to="/portfolio/one">Look at my work</router-link></button>
    </div>
    <div class="right-content">
      <p>I am passionate about building excellent Web Applications that improves the lives of those around me. I specialize in creating software for clients ranging from individuals and small-businesses all the way to large enterprise corporations.</p>
      <p> All of my work is produced locally from Pakistan, Gujrat. What would you do if you had a software expert available at your fingertips?</p>
       </div>
  </div>
</template>

<style lang="scss" scoped>

  .left-content {
    background-color: #ffe476;
  }

  .right-content {
    background: #fff;
    padding: 50px;
    margin-top: 80px;
    display: block;
  }

  button {
    font-size: 1.5em;
    margin-top: 100px;
  }

  .subtxt {
    font-size: 1.5em;
    margin-top: 30px;
  }

</style>
