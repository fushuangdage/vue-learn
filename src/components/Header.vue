<template>
  <h1>{{title}}</h1>

</template>

<script>
  export default {
    name: "Header",
    data() {
      return {
        title: "Vue.js Demo"
      }
    }
  }
</script>

<style scoped>
  h1 {
    background: lightgreen;
    padding: 10px;
    text-align: center;
  }


</style>
