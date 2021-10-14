<template>
  <div class="Main">

      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            <div id="title">
                <h2>Why Work With Me</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if ">web . brending .ux/ui</h6>
            </div> 
            <section class="line"></section>
            <div id="title">
                <h6 class="text-uppercase if why col-12">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Praesentium impedit quis unde, ratione ad totam non repellat, harum magni,
                    dolorem dicta accusamus ab at quia nesciunt ipsam aliquid? Labore, minus.
                    Praesentium impedit quis unde
                </h6>
            </div> 
        </div>
      </div>

      <div class="container-fluid sectionOneMain">
          <div class="container">
              <div class="row">
              <div class="col-4 loremMainOne">
                  <h6 class="if">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                  </h6>
              </div>
              <div class="col-4 loremMainOne">
                  <h6 class="if">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                  </h6>
              </div>
              <div class="col-4 loremMainOne">
                  <h6 class="if">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                  </h6>
              </div>
          </div>

          </div>
          
      </div>
   
  </div>
</template>



<script>
export default {
  name: 'MainSectionTwo',
  props: {
   
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.sectionOneMain {
    background-color: #16181f;
    color: white;
}

.bloccoTitolo {
    text-align: center;
    padding-top: 80px;
    padding-bottom: 10px;
    color: white
}

.loremMainOne {
    padding: 40px;
    padding-bottom: 60px;
}

.if {
    font-size: 10px;
    color: #6e89a0;
    line-height: 20px;
    padding: 15px;
}

.why {
    padding-left: 30%;
    padding-right: 30%;
    padding-top: 30px;
}

</style>
