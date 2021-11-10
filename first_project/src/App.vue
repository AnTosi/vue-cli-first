<template>
  <div id="app">
    <div>
      <firstTitle/>
    </div>

    <div class="hero_container">
      <img src="./assets/dune.jpg" alt="">
      <jumbotron/>
    </div>
  </div>
</template>

<script>
  import firstTitle from './components/Title.vue';
  import jumbotron from './components/Hero.vue';

  export default {
    name: 'App',
    components: {
      firstTitle,
      jumbotron
    }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.hero_container img {
  object-fit: cover;
  width: 100vw;
}

.hero_container {
  position: relative;
}
</style>
