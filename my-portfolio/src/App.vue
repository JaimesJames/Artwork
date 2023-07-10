<template>
  <NavBar/>
  <h1>ค่าย</h1>
  <ContentVer1/>
  <h1>ผลงาน</h1>
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContentVer1 from './components/ContentVer1.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    ContentVer1
  }
}
</script>

<style>
#app {
  font-family: 'Noto Sans Thai', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  text-align: center;
}
h1{
  font-size: 100px;
}
</style>
