<template>
  <footer>
    {{ Copyright }}
  </footer>
</template>

<script>
export default {
  name: 'footerNormal',
  props: {
    Copyright: {
      type: String,
      default: '(c) Copyright'
    }
  },
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 10px;
  background: #f1f1f1;
  text-align: center;
}
</style>
