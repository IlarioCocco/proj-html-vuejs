<template>
  <div class="Main">

      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            <div id="title">
                <h2>Recent Work</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if ">web - brending - ux / ui</h6>
            </div> 
              <div>
                <span class="line"></span>
            </div>
        </div>
      </div>

  </div>
</template>


<script>
export default {
  name: 'MainSectionTree',
  props: {
   
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.sectionOneMain {
    background-color: #96c577
;
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
