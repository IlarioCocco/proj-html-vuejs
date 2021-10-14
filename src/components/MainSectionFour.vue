<template>
<div>

    <div class="mainSectionFour d-flex">
      <div class="sectionOneImgLeft">
      </div>
       <div class="sectionOneImgRight">
      </div>
    </div>

    <div class="sectionImgTwo d-flex">
      <div class="sectionTwoImgLeft">
      </div>
       <div class="sectionTwoImgRight">
      </div>
    </div>

     <div class="sectionImgTree d-flex">
      <div class="sectionTreeImgLeft">
      </div>
       <div class="sectionTreeImgRight">
      </div>
    </div>

    <div class="view text-uppercase text-center if">
        <p>view all work</p>
    </div>

</div>
  
</template>

<script>
export default {
  name: 'MainSectionFour',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.sectionOneImgLeft {
    background-image: url('../assets/img/portfolio1_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.sectionOneImgRight {
    background-image: url('../assets/img/portfolio5_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.sectionTwoImgLeft {
    background-image: url('../assets/img/portfolio4_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.sectionTwoImgRight {
    background-image: url('../assets/img/portfolio3_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.sectionTreeImgLeft {
    background-image: url('../assets/img/portfolio2_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.sectionTreeImgRight {
    background-image: url('../assets/img/portfolio6_featured_item-800x640.jpg');
    background-position: right;
    background-size: cover;
    height: 500px;
    width: 50%;
}

.view{
   padding: 40px;
   background: #f9245b;
   color: white;
   line-height: 15px;
   margin-bottom: 0px;
}

p {
    margin-bottom: 0px;
}





</style>
