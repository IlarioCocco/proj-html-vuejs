<template>
  <div class="Main">

      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            <div id="title">
                <h2>{{title}}</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if ">web . brending .ux/ui</h6>
            </div>
            <div>
                <span class="line"></span>
            </div>
            
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
          <div class="container text-center">
              <div class="row">

                <div class="col-4 loremMainOne">
                    <div id="circle">
                        <img class="icon" src="../assets/img/logo_demo_1.png" alt="">
                        <div>
                            <h6 class="text-uppercase brand">web design</h6>
                        </div>
                    </div>
                </div>

                <div class="col-4 loremMainOne">
                    <div id="circle">
                        <img class="icon" src="../assets/img/logo_demo_1.png" alt="">
                        <div>
                            <h6 class="text-uppercase brand">branding</h6>
                        </div>
                    </div>
                    
                </div>

                <div class="col-4 loremMainOne">
                    <div id="circle">
                        <img class="icon" src="../assets/img/logo_demo_1.png" alt="">
                        <div>
                            <h6 class="text-uppercase brand">ui 7 ux</h6>
                        </div>
                    </div>
                </div>

              </div>
          </div>
      </div>
      
  </div>
</template>



<script>
export default {
  name: 'MainSectionTwo',
    props: [
        'title'
        ]
}

</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#circle {
    width: 200px;
    height: 200px;
    background: rgba(255, 0, 0, 0);
    border-radius: 50%;
    border: 8px solid  #f9245b;
}

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
    padding-bottom: 100px;
}

.if {
    font-size: 10px;
    color: #6e89a0;
    line-height: 20px;
}

.why {
    padding-left: 30%;
    padding-right: 30%;
    padding-top: 30px;
}

.container {
    width: 65%;
    display: flex;
    justify-content: center
    
}

.brand {
    padding-top: 100px;
    font-size: 10px;
}

.icon {
    padding-top: 50px;
}



</style>
