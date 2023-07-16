<template>
  <div class="bar">
    <h3 onclick:="num()">หน้าแรก</h3>
    <h3>แนะนำตัว</h3>
    <h3>ค่าย</h3>
    <h3>ผลงาน</h3>
    <h3>เหลา</h3>
  </div>
  <CarouselTemp />

  <h1>ค่าย</h1>
  <ContentVer1 />
  <h1>ผลงาน</h1>
</template>

<script>
import CarouselTemp from "./components/CarouselTemp.vue";
import ContentVer1 from "./components/ContentVer1.vue";

export default {
  name: "App",
  components: {
    CarouselTemp,
    ContentVer1
  }
};

</script>

<style>
#app {
  font-family: 'Inter', sans-serif;
  font-family: 'Kanit', sans-serif;
  font-family: 'Noto Sans Thai', sans-serif;
  color: #2c3e50;
  text-align: center;
}
h1 {
  font-size: 100px;
}

.bar{
    margin: 20px calc(50% - 25%);
    width: 50%;
    height: 40px;
    display: flex;
    position: fixed;
    background-color: hsl(0,50%,0%,30%);
    border-radius: 50px; 
    z-index: 100;
    gap: 50px;
}

.bar h3{
    margin: 0;
    color: rgb(255, 255, 255);
    font-weight: 300;
    flex: 1;
    padding-top: 6px;
    border-radius: 20px;
    

 }
 .bar h3:hover{
    margin: 0;
    color: rgb(24, 24, 24);
    flex: 1;
    background-color: rgb(46, 253, 39);
    font-weight: 600;

 }
</style>
