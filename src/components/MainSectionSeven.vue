<template>
 
<div>
    <div class="dimensionOne d-flex">
        <div class="oneImg">
        </div>
        <div class="twoImg">
        </div>
        <div class="treeImg">
        </div>
    </div>

    <div class="container-fluid blocText">
         <div class="row row-cols-lg-3 bloccoLorem">
             <div>
                 <h6>Live The Design Process</h6>
                    <h6 class="if secondText">What's to come next? Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Perspiciatis est nulla sequi ut ratione eos iste accusamus vero,
                        ipsum officiis aspernatur porro sint! Aut, aliquam quo. Quibusdam corporis quas quae!
                    </h6>
             </div>

              <div>
                 <h6 >What's next of the App Store?</h6>
                    <h6 class="if secondText">What's to come next? Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Perspiciatis est nulla sequi ut ratione eos iste accusamus vero,
                        ipsum officiis aspernatur porro sint! Aut, aliquam quo. Quibusdam corporis quas quae!
                    </h6>
             </div>

              <div>
                 <h6>The Humble Wooden Desk</h6>
                    <h6 class="if secondText">What's to come next? Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Perspiciatis est nulla sequi ut ratione eos iste accusamus vero,
                        ipsum officiis aspernatur porro sint! Aut, aliquam quo. Quibusdam corporis quas quae!
                    </h6>
             </div>
        </div>

    </div>
</div>
      
    

</template>

<script>
export default {
  name: 'MainSectionSeven',
  props: {
    msg: String
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.oneImg {
    background-image: url('../assets/img/blog3-featured-400x267.jpg');
    background-position: right;
    background-size: cover;
    height: 300px;
    width: 35%;
}


.twoImg {
    background-image: url('../assets/img/blog2-featured-400x267.jpg');
    background-position: right;
    background-size: cover;
    height: 300px;
    width: 35%;
}


.treeImg {
    background-image: url('../assets/img/blog1-featured-400x267.jpg');
    background-position: right;
    background-size: cover;
    height: 300px;
    width: 35%;
}
  

.blocText {
    padding-top: 20px;
    background: #191c23;
    color: #f9245b;
}  

.secondText {
    color: rgb(111, 135, 148);
    line-height: 20px;
    padding-bottom: 20px;
}

</style>
