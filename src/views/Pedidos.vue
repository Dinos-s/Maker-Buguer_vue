<template>
  <div class="main-container">
    <h1>Pedidos</h1>
    <Dashboard/>
  </div>
</template>

<style scoped>
  
</style>

<script>
  import Dashboard from "../components/Dashboard";
  export default{
    name: "Pedidos",
    components:{
      Dashboard,
    }
  }
</script>