<template>
    <div class="container">
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
    </div>
  
</template>

<script>
export default {
    name: 'ContentVer1'
}
</script>

<style scoped>
    .container{
        display: grid;
        grid-template-columns: auto auto auto;
        justify-content: center;
        gap: 20px;
    }
    .card{
        width: 200px;
        height: 200px;
        background: black;
    }
</style>