<template>
  <div class="mainSectionFive container-fluid">
      <div class="logoApici">
          <img class="logoApici" src="../assets/img/quotes-1.png" alt="">
          <h6 class="if">"That been one of my mantras - focus and simplicity. Simple can be harder than complex;
              you have to work hard to get your <br>
              thinkinh clean make itsimple."</h6>
          <h6>STEVE JOBS - APPLE</h6>
          <h6 class="text-uppercase trusted">trusted by global brands</h6>
      </div>

      <div class="container">
          <div class="row row-cols-lg-5 bloccoLorem">

              <div class="logoLorem text-center">
                  <img class="dimensionOne" src="../assets/img/logo_demo_1.png" alt="">
              </div>
              <div class="logoLorem text-center">
                  <img class="dimensionTwo" src="../assets/img/logo_demo4.png" alt="">
              </div>
              <div class="logoLorem text-center">
                  <img class="dimensionTree" src="../assets/img/Vector_Smart_Object-1.png" alt="">
              </div>
              <div class="logoLorem text-center">
                  <img class="dimensionFour" src="../assets/img/Vector_Smart_Object-2.png" alt="">
              </div>
              <div class="logoLorem text-center">
                  <img class="dimensionFive" src="../assets/img/Vector_Smart_Object-3.png" alt="">
              </div>

          </div>
      </div>
      
    
  </div>
</template>

<script>
export default {
  name: 'MainSectionFive',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.mainSectionFive {
    background-image: url('../assets/img/testimonial_bkgd.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: repeat;
    height: 600px;
}   

.logoApici {
    text-align: center;
    padding-top: 50px;
    color:white;
    max-width: 100%;
    max-height: 100px;
}

.bloccoLorem {
    padding-top: 35%;
    max-width: 75%;
    margin: auto;
}

.dimensionOne {
    width: 50px;
}

.dimensionTwo {
    width: 60px;
}

.dimensionTree {
    width: 45px;
}

.dimensionFour {
    width: 40px;
}

.dimensionFive {
    width: 50px;
}

.if {
    padding-top: 20px;
}

.trusted {
    padding-top: 150px;
}


</style>
