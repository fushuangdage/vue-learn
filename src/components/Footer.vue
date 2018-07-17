<template>
  <footer>
    <p>{{copyright}}</p>
  </footer>
</template>

<script>
  export default {
    name: "app-footer",
    data() {
      return {
        copyright: "copyright 2017 01 01"
      }
    }
  }
</script>

<style scoped>
  p {
    background: lightgreen;
    padding: 10px;
    text-align: center;
  }


</style>
