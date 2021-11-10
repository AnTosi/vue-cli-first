<template>
  <div id="app">
      <firstTitle/>
      <jumbotron/>
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
</style>
