<template>
  <header>
    <div class="left-header">
      <h1>Ivan Biedermann</h1>
      <h2>Technicien orienté développement</h2>
      <h3>418 - I'm a teapot !</h3>
    </div>
    <div class="right-header">
      <div class="img">
        <img src="./../assets/img/pp.jpg">
      </div>
    </div>
  </header>
</template>

<script>
export default {
  
}
</script>

<style scoped>
header{
  height:100vh;
  width: 100%;
  display:flex;
  flex-direction: row;
  align-items:center;
  justify-content: center;
  background-image: url('./../assets/img/header.jpg');
  background-position: center;
  background-size:cover;
  background-repeat:no-repeat;
  background-color:#2c3e50;
  color:#f5f5f5;
  position:relative;
  z-index:1;
}

header::before{
  content:'';
  display:block;
  z-index:2;
  height:100vh;
  width:100%;
  position:absolute;
  top:0;
  left:0;
  background: -moz-linear-gradient(180deg, rgba(44,62,80,0.7) 0%, rgba(44,62,80,0.3) 70%, rgba(44,62,80,0.05) 100%);
  background: -webkit-linear-gradient(180deg, rgba(44,62,80,0.7) 0%, rgba(44,62,80,0.3) 70%, rgba(44,62,80,0.05) 100%);
  background: linear-gradient(180deg, rgba(44,62,80,0.7) 0%, rgba(44,62,80,0.3) 70%, rgba(44,62,80,0.05) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#2c3e50",endColorstr="#2c3e50",GradientType=1);
}

header h1{
  font-size: 4.3vw;
  text-transform: uppercase;
  font-weight:100;
}

header > div{
  position:relative;
  z-index:3;
  margin:50px;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-direction:column;
}

div.right-header .img{
  width:200px;
  height:200px;
  overflow:hidden;
  border-radius:200px;
  border:3px solid #f5f5f5;
  box-shadow:0 3px 6px rgba(0,0,0,.16), 0 3px 6px rgba(0,0,0,.23);
}
</style>