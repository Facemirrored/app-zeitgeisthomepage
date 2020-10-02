<template>
  <div id="app">
    <Header></Header>
    <div class="left-container">
      <div class="row">
        <div class="col-lg-2 col-lg-10 ">
          <img class="img-fluid" style="width: 50%; height: 50%" src="./assets/logo.svg">
        </div>
      </div>
    </div>
  </div>
</template>

<script>

  import Header from "./components/Header";

  export default {
    name: 'App',
    components: {Header},
    data() {
      return {
      }
    }
  }
</script>

<style>
  body{
    background-image: url("./assets/backgournd3.jpg");
    background-position: left;
    background-attachment: fixed;
    background-repeat: no-repeat;
  }
</style>
