<template>
    <div class="flex">
        <div class="el1"><img class="img" src="https://img.icons8.com/external-others-phat-plus/256/external-cruise-marketing-outline-others-phat-plus.png" alt=""><p class="info">Our Cruises</p> <p class="p2e">Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies</p></div>
        <div class="el"><img class="img" src="https://img.icons8.com/wired/256/geography.png" alt=""><p class="info">Amazing Travel</p><p class="p2e">Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies</p></div>
        <div class="el"><img class="img" src="https://img.icons8.com/external-pseudo-solid-zulfa-mahendra/1x/external-sensor-electric-car-pseudo-solid-zulfa-mahendra.png" alt=""><p class="info">Book Your Trip</p><p class="p2e">Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies</p></div>
        <div class="el"><img class="img" src="https://cdn-icons-png.flaticon.com/512/4245/4245231.png" alt=""><p class="info">Nice Support</p><p class="p2e">Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies</p></div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.flex{
    display: flex;
    justify-content: center;
    width: 100%;
    
}
.el{
   
    background-color: aliceblue;
    width: 100%;
    display:flex;
    flex-direction: column;
    margin: 0;
    text-align: center;
    letter-spacing: 1px;

    
}
.el1{
   
    background-color: rgba(4, 226, 255, 0.963);
    width: 100%;
    display:flex;
    flex-direction: column;
    margin: 0;
    text-align: center;
    letter-spacing: 1px;


}
.img{
    margin-left: 25%;
    margin-top: 20%;
    width: 50%;
    height: 50%;
    margin-bottom: 0;

}
.info{
    font-size: 25px;
    text-align: center;
    margin: 0;
}
.p2e{
    text-align: center;
    font-size: 10px;
    display: block;
    width: 50%;
    color: black;
    margin-left: 25%;
   
}
</style>