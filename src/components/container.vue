<template>
  <div class="container">
    <el-container>
      <el-header class="sn-header">SnippetBook</el-header>
      <el-container>
        <el-aside class="sn-side" width="200px">Aside</el-aside>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>

export default {
  name: 'container',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.sn-header {
  padding: 10px;
  background: #333;
  color: #fff;
  font-size: 2.5rem;
  letter-spacing: 2px;
}

</style>
