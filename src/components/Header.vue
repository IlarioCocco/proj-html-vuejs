<template>
  <div class="Header">
      <img class="logo" src="../assets/av-freelance-logo-retina.png" alt="">
  </div>
</template>



<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.logo {
    width: 50px;
}
   

</style>
