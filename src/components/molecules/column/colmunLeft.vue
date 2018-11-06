<template>
  <div class="colmunLeft">
    <sidebarNormal class="leftSide" />
    <mainNormal class="contentWrap" />
  </div>
</template>

<script>
import sidebarNormal  from '@/components/molecules/column/sidebar/sidebarNormal'
import mainNormal  from '@/components/molecules/column/main/mainNormal'

export default {
  name: 'colmunLeft',
  components : {
    sidebarNormal,
    mainNormal
  },
  props: {

  },
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.colmunLeft {
  padding-top: 70px;
  display: flex;
  .leftSide {
    width: 20%;
  }
  .contentWrap {
    width: 80%;
  }
}
</style>
