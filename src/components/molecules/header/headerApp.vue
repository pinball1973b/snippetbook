<template>
  <header>
    <h1>{{sitename}}</h1>
  </header>
</template>

<script>
export default {
  name: 'headerApp',
  props: {
    sitename: {
      type: String,
      default: 'sitename'
    }
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 10px;
  background: #f1f1f1;
  h1 {
    margin: 0;
    padding: 0;
    font-weight: normal;
  }
}
</style>
