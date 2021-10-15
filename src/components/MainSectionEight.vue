<template>
  <div class="Main">
      <div class="sectionOneMain">
        <div class="bloccoTitolo">
            
            <div id="title">
                <h2>{{title}}</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if ">tell me more about your project</h6>
            </div> 
            <div>
                 <section class="line dark"></section>
            </div>
            <div id="title">
                <h6 class="text-uppercase if why col-12">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Praesentium impedit quis unde, ratione ad totam non repellat, harum magni.
                </h6>
            </div>

            <div class="blocInput">
                <div>
                    <input class="input" type="text" placeholder="  NAME*"> 
                </div>

                <div>
                    <input class="input" type="text" placeholder="  EMAIL*"> 
                </div>

                <div>
                    <input class="input" type="text" placeholder="  PHONE"> 

                </div>
                <div>
                    <input class="input danger" type="text" placeholder="LET'S TALK"> 
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

.sectionOneMain {
    background-color: #ebeced;
}

.bloccoTitolo {
    text-align: center;
    padding-top: 80px;
    color: rgb(0, 0, 0)
}

.loremMainOne {
    padding: 40px;
    padding-bottom: 60px;
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

.dark {
    background: rgb(149, 177, 186);
}

.blocInput {
    padding-top: 10px;
    padding-bottom: 80px;
}


.input { 
    border: none;
    width: 25%;
    font-size: 10px;
    margin-top: 20px;
    line-height: 30px;
}

.danger  {
    background: #f9245b;
    text-align: center;
    font-size: 15px;
}

::placeholder {
    color: rgb(213, 213, 213)
}

</style>
