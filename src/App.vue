<template>
<!-- Utilizzazione -->
  <div id="app">
    <Header :bgImage="require('./assets/img/banner_images.jpg')" title="Art Director"/>
    <Main/>
    <MainSectionTwo/>
    <MainSectionThree/>
    <MainSectionFour/>
    <MainSectionFive/>
    <MainSectionSix/>
    <MainSectionSeven/>
    <MainSectionEight/>
    <Footer/>
  </div>
</template>




<script>
// importazione 
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import MainSectionTwo from './components/MainSectionTwo.vue';
import MainSectionThree from './components/MainSectionThree.vue';
import MainSectionFour from './components/MainSectionFour.vue';
import MainSectionFive from './components/MainSectionFive.vue';
import MainSectionSix from './components/MainSectionSix.vue';
import MainSectionSeven from './components/MainSectionSeven.vue';
import MainSectionEight from './components/MainSectionEight.vue';
import Footer from './components/Footer.vue';



// registrazione 
export default {
  name: 'App',
  components: {
    Header,
    Main,
    MainSectionTwo,
    MainSectionThree,
    MainSectionFour,
    MainSectionFive,
    MainSectionSix,
    MainSectionSeven,
    MainSectionEight,
    Footer,
  }
}
</script>




<style lang="scss">
@import "./assets/scss/common.scss";
@import "~bootstrap/scss/bootstrap";
@import "./assets/scss/variables.scss";
</style>
