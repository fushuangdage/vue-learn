<template>
  <div id="app">
    <fs_header></fs_header>
    <h1>{{title}}</h1>
    <users></users>
  </div>
</template>

<script>

  import Header from './components/Header'
  import Users from './components/User'

  export default {
    name: 'App',
    data() {
      return {
        title: "这是我的第一个vue"
      }
    },
    components: {
      "users": Users,
      "fs_header":Header
    }

  }
</script>

<style scoped>
  h1 {
    color: purple;
  }
</style>
