<template>
  <section class="jumbotron">
    <img src="../assets/vue-js-kk.jpg" alt="">
  </section>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron {
  width: 100%;
  height: 80vh;
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
}
</style>
