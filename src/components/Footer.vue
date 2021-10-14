<template>
  <div class="Footer">

    <div class="boxFooter d-flex justify-content-center">
      <img  class="logoAv" src="../assets/img/avada-footer-logo-66x66.png" alt="logo av">
    </div>

    <div class="boxFooter d-flex justify-content-center">
      <h6 class="if fw-lighter">Copyright 2012 - 2021 | Avada Theme by <span class="fw-bold light">Theme Fusion</span>  |  All Rights Reserved  |  Powered by <span  class="fw-bold light">WordPress</span> 
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
  padding-bottom: 50px;
}

.if {
  color: rgb(123, 136, 157)
}

.light {
  color: white;
}


</style>
