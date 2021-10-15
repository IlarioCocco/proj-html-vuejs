<template>
<!-- Utilizzazione -->
  <div id="app">
    <Header :bgImage="require('./assets/img/banner_images.jpg')" title="Art Director"/>
    <Main title="About Me"/>
    <MainSectionTwo title="Why Work With Me"/>
    <MainSectionThree title="Recent Work"/>
    <MainSectionFour/>
    <MainSectionFive :bgImage="require('./assets/img/testimonial_bkgd.jpg')" title="trusted by global brands" />
    <MainSectionSix title="Expert Design Advice"/>
    <MainSectionSeven/>
    <MainSectionEight title="Let's Work Together"/>
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
