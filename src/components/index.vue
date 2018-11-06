<template>
<div class="wrap">
  <headerNormal />
  <colmunLeft />
  <footerNormal />
</div>
</template>

<script>
import headerNormal  from '@/components/molecules/header/headerNormal'
import colmunLeft  from '@/components/molecules/column/colmunLeft'
import footerNormal  from '@/components/molecules/footer/footerNormal'

export default {
  name: 'Index',
  components: {
    headerNormal,
    colmunLeft,
    footerNormal
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  margin: 0;
}
</style>
