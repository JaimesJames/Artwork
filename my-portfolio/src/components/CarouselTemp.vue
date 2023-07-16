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
    width: 100%;
    height: 40vw;
    text-align: center;
    border-radius: 25px;
    position: relative;
    
}
 h1{
    color: rgb(255, 255, 255);
    align-items: center;
    margin: 0;
    font-size: 20vw;
    font-weight: 600;
    position: absolute;
    top:100px;
    left: calc(50% - 42vw);
    

 }
</style>