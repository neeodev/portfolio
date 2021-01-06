<template>
  <div>
    <Header></Header>
    <Menu></Menu>
  </div>
</template>

<script>
import Header from './components/Header'
import Menu from './components/Menu'

export default{
  components: {
    Header,
    Menu,
  }
}
</script>

<style>
*{
  font-family: 'Roboto', Helvetica !important;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
