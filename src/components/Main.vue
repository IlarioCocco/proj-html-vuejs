<template>
  <div class="Main">

      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            <div id="title">
                <h2>About Me</h2>
            </div>  
            <div id="title ">
                <h6 class="text-uppercase if">ui & ux expert</h6>
                <section class="line"></section>
            </div> 
        </div>
      </div>

      <div class="container-fluid sectionOneMain">
          <div class="container">
              <div class="row">
              <div class="col-6 loremMainOne">
                  <h6 class="if">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                      <h6></h6>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                  </h6>
              </div>
              <div class="col-6 loremMainOne">
                  <h6 class="if">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                      Sapiente unde quia cum placeat exercitationem molestias, 
                      non, excepturi culpa magni molestiae nemo, nostrum delectus ullam. 
                      Excepturi sed autem quasi eius porro!
                      <h6></h6>
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
  name: 'Main',
  props: {
   
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.sectionOneMain {
    background-color: #20232c;
    color: white;
    
}

.bloccoTitolo {
    text-align: center;
    padding-top: 90px;
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




</style>
