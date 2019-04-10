<template>
<div id="app">
  <navbar />
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
body {
    margin: 0;
}

#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;

    margin: 0;
}
</style>
