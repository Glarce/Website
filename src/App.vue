<template>
<div id="app">
  <nav-bar />
  <router-view />
</div>
</template>

<script>
import NavBar from './components/Nav.vue'

export default
{
	components:
  {
  	NavBar
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

p {
    font-size: 15pt;
}

h2 {
    font-family: 'Roboto', sans-serif;
    font-size: 50pt;

    margin-top: 67px;
    text-align: center;

    color: #707070;
}

#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;

    margin: 0;
}
</style>
