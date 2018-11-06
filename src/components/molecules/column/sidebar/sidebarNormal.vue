<template>
  <div class="sidebarNormal">
    <ul>
      <li
        v-for="list in lists"
        :key="list.name"
      >
        <a :href="list.url">
          {{ list.name }}
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'sidebarNormal',
  data() {
    return {
      lists: [
        { name: "hoge" , url: "hoge.com" },
        { name: "fuga" , url: "fuga.com" },
        { name: "piyo" , url: "piyo.com" },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
.sibebarNormal {
  background: #fafafa;
  padding: 10px;
}
</style>
