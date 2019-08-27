<template>
  <div class="hello">
    <Header />
  </div>
</template>

<script>
import Header from './Header'
export default {
  name: 'HelloWorld',
  components: {
    Header
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
