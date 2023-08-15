<template>
    <div class="container">
        <h1>Portfolio</h1>
    </div>
</template>

<script> 
export default {
    name: 'CarouselTemp'
}
</script>

<style scoped>
.container{
    background-image: url("../assets/corousel.png");
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 40vw;
    text-align: center;
    border-radius: 25px;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
 h1{
    color: rgb(255, 255, 255);
    font-size: 10vw;
    font-weight: 600;
    font-family: 'Roboto', sans-serif;
    
    

 }
</style>