<template>
  <div class="users">
    <ul>
      <li v-for="user in users">
       <h1> {{user}}</h1>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: "User",
    data() {
      return {
        users:["aaa","bbb","ccc"]
      }
    }
  }
</script>

<style >
  h1{
    color: deepskyblue;
  }
</style>
