<template>
<div id="app">
  <nav />
  <router-view />
</div>
</template>

<script>
import Nav from './components/Nav.vue'

export default
{
  components:
  {
    Nav
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Roboto');

@import "./styles/vars";
body {
    margin: 0;

    overflow-x: hidden;
}

h2 {
    font-family: 'Roboto', sans-serif;
    font-size: 50pt;

    margin-top: 67px;

    color: $darkGrey;
}

#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;

    margin: 0;
}
</style>
