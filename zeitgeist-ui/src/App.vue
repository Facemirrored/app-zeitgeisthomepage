<template>
  <div id="app">
    <Header></Header>
    <div class="left-container">
      <div class="row">
        <div class="col-md-2">
          <img class="logo" src="./assets/logo.svg">
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
      return {}
    }
  }
</script>

<style>
  body {
    background-image: url("./assets/backgournd3.jpg");
    background-position: left;
    background-attachment: fixed;
    background-repeat: no-repeat;
  }

  .logo {
    padding-top: 50px;
    padding-left: 10px;
    padding-right: 10px;
    height: auto;
    display: block;
    width: 30%;
  }


  @media screen and (min-width: 1200px) {
    .logo {
      width: 30%;
    }
  }
</style>
