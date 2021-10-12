<template>
  <div class="Header">
      <img class="logo" src="../assets/img/av-freelance-logo-retina.png" alt="">
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
.Header {
    height: 200px;
    background-color: black;
    width: 100%;
}

.logo {
    width: 80px;
}
   

</style>
