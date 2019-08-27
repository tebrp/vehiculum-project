<template>
  <div class="header">
    <img src="~/../assets/images/header/logo-horizontal.png" class="logo">
    <div class="header-right">
      <a class="active" href="#home">Home</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
</template>
<style lang="scss">
  @import "./src/assets/styles/common/_header.scss";
</style>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
