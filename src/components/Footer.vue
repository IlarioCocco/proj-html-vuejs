<template>
  <div class="Footer">

    <div class="boxFooter d-flex justify-content-center">
      <img  class="logoAv" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
    </div>

    <div class="boxFooter d-flex justify-content-center">
      <h6 class="if">Lorem ipsum dolor sit, amet consectetur adipisicing elit.
        amet consectetur adipisicing elit.
      </h6>
    </div>

    <div class="boxFooterIcon d-flex justify-content-center">
      <img  class="logoAvSmall" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
      <img  class="logoAvSmall" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
      <img  class="logoAvSmall" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
      <img  class="logoAvSmall" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
    </div>
   
  </div>
</template>



<script>
export default {
  name: 'Footer',
  props: {
   
  }
}
</script>


}



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.boxFooter {
  padding-top: 50px;
  background: #191c23;
  color: white;
}
  

.logoAvSmall {
  width: 25px;
  margin: 5px;
}

.boxFooterIcon {
  padding-top: 10px;
  background: #191c23;
  color: white;
  padding-bottom: 50px;
}

</style>
