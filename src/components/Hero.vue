<template>
  <div class="hero">
    <img src="../assets/logo.png">
    <div class="vue-info">
        <h1>The Progressive JavaScript Framework </h1>
        <a href="https://vuejs.org/" target="blank">Vai al Sito</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<style scoped lang="scss">
    * {
        margin:0;
        padding:0;
        box-sizing:border-box;
    }
    .hero{
        height:400px;
        margin: 0 auto;
        background-color:#C0C0C0;
        display:flex;
        justify-content: center;
        align-items:center;
        padding:20px;
    }
    img{
        width:200px;
    }
    .vue-info{
        display:flex;
        flex-direction:column;
        align-items:center;
        padding:50px;
    }
    a:link, a:visited{
        width:150px;
        margin-top:20px;
        text-decoration: none;
        color:#333;
        background-color:#00cc00;
        padding:30px;
    }
</style>
