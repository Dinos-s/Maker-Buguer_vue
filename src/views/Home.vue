<template>
  <Banner/>
  <div class="main-container">
    <h1>Monte o seu Hamburger:</h1>
    <Form/>
  </div>
</template>

<style>

</style>

<script>
  import Banner from "../components/Banner.vue";
  import Form from "../components/Form.vue";
  export default{
    name: 'Home',
    components: {
      Banner,
      Form,
    }
  }
</script>
