<template>
  <nav>
    <ul class="menu align-right">
      <li><a href="#">Hello world</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  watch: {
  },
  
}
</script>

<style scoped>

nav{
  position:fixed;
  height:6vh;
  top:0;
  left:0;
  width:100%;
  z-index:10;
  background-color:#f5f5f5;
  box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
  transition:all 0.3s, transform 0.3s;
}

nav ul{
  height:100%;
}

nav ul li a{
  display:flex;
  align-items:center;
  justify-content:center;
}

</style>