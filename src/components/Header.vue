<template>
  <div class="bg"></div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg {
  /* The image used */
  background-image: url('../assets/bkgrnd.jpg');

  /* Full height */
  height: 85vh;

  opacity: 0.95;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
