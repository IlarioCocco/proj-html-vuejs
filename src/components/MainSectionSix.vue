<template>
  <div class="Main">

      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            <div id="title">
                <h2>Expert Design Advice</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if ">trnding design news</h6>
                <div>
                    <span class="line"></span>
                </div>
            </div> 
            
        </div>
      </div>

  </div>
</template>


<script>
export default {
  name: 'MainSectionSix',
  props: {
   
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.sectionOneMain {
    background-color:#49629b;
    color: white;
}

.bloccoTitolo {
    text-align: center;
    padding: 50px;
    color: white
}

.loremMainOne {
    padding: 40px;
    padding-bottom: 60px;
}

.if {
    font-size: 10px;
    color: #ffffff;
    line-height: 20px;
    padding: 15px;
}
</style>