<template>
  <div class="bar">
    <h3>หน้าแรก</h3>
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
  font-family: "Noto Sans Thai", sans-serif;
  color: #2c3e50;
  text-align: center;
}
h1 {
  font-size: 100px;
}

.bar{
    margin: 20px calc(50% - 35%);
    width: 70%;
    height: 50px;
    display: flex;
    position: fixed;
    background-color: hsl(0,50%,100%,20%);
    border-radius: 50px; 
}

.bar h3{
    margin: 0;
    color: white;
    font-weight: 400;
    flex: 1;
    padding-top: 12px;

 }
 .bar h3:hover{
    margin: 0;
    color: rgb(55, 52, 87);
    font-weight: 400;
    flex: 1;

 }
</style>
