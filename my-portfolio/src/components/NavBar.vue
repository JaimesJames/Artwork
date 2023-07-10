<template>
    <div class="container">
        <div class="bar">
            <h3>หน้าแรก</h3>
            <h3>แนะนำตัว</h3>
            <h3>ค่าย</h3>
            <h3>ผลงาน</h3>
            <h3>เหลา</h3>
        </div>
        <h1>Portfolio</h1>
    </div>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style scoped>
.container{
    background-image: url("../assets/test1.jpg");
    background-attachment: fixed;
    width: 100%;
    height: 30vw;
    text-align: center;
    
}
.bar{
    padding-top: 1vw;
    margin: auto;
    width: 70%;
    display: flex;
}
 h1{
    color: rgb(255, 255, 255);
    align-items: center;
    margin: 0;
    font-size: 400px;
    font-weight: 600;

 }
 .bar h3{
    margin: 0;
    color: white;
    font-weight: 400;
    flex: 1;

 }
 .bar h3:hover{
    margin: 0;
    color: rgb(195, 191, 240);
    font-weight: 400;
    flex: 1;

 }
</style>