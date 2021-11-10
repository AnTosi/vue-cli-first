<template>
    <div class="hero_container">
        <img src="../assets/dune.jpg" alt="">
      <div class="hero_text">
        <h2>Dune</h2>
        <p>
          Sto film spacca, andatelo a guardare perché lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam possimus ducimus accusamus?
        </p>
      </div>
    </div>
</template>

<script>

    export default {
        name: 'jumbotron',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hero_text {
    position: absolute;
    bottom: 4rem;
    left: 4rem;
    color: white;
    font-size: 3rem;
  }

  h2 {
    text-align: left;
    margin-bottom: 0.5rem;
  }

  p {
    margin: 0;
    text-align: left;
    width: 70%;
  }

  .hero_container img {
    object-fit: cover;
    width: 100%;
  }

  .hero_container {
    position: relative;
  }
</style>
