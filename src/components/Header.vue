<template>
<div>

    <div id="Header">

        <div class="d-flex justify-content-between">
            <img class="logo" src="../assets/img/av-freelance-logo-retina.png" alt="">
            <img class="logo" src="../assets/img/av-freelance-logo-retina.png" alt="">
        </div>
      
        <div class="bloccoTitolo">
            <div id="title">
                <h5 class="text-uppercase">{{title}}</h5>
            </div> 
            <div id="title">
                <h2>Art Director</h2>
            </div>  
            <div id="title">
                <h6 class="text-uppercase if">if it doesn't challenge you, it doesn't change you</h6>
            </div> 
        </div>

    </div>
        
</div>

</template>


<script>

export default {
  name: 'Header',
  props: [
      'title'
    ]
}

</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#Header {
    background-image: url('../assets/img/banner_images.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: repeat;
    height: 600px;
    

    .logo {
    margin: 40px;
    width: 120px;
    }
    
}


#title {
    display: flex;
    justify-content: center;

    h2 {
        font-size: 100px;
        color: #f9245c;
    }

    h5 {
        color: white;
    }

    h6 {
        color: rgb(64, 64, 78);
    }
}

.bloccoTitolo{
    margin-top: 140px;
}

.if {
    font-size: 13px;
}



</style>
