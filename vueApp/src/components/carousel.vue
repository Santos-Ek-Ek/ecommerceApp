
<template >


    <div id="carouselExampleRide" class="carousel slide" data-bs-ride="true">

        <div class="carousel-inner">
            <div id="item1" class="carousel-item active">
            
            </div>
            <div id="item2" class="carousel-item">
            
            </div>
            <div id="item3" class="carousel-item">
            
            </div>
        </div>
        
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleRide" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleRide" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>


    


    


</template>



<script>

export default{
    name: 'carousel'
}


</script>

<style scoped>

#carouselExampleRide {
    padding: 0;
}
.carousel-item{
    height: 34rem;
    position: relative;
    background-image: url(../assets/image1.jpg);
    background-position: center;
    background-size: cover;
}

#item2 {
    background-image: url(../assets/image2.jpg);
}

#item3 {
    background-image: url(../assets/image3.jpg);
}



</style>

