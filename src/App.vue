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

    padding-top: 67px;
    padding-bottom: 67px;
    margin-top: 0;
    margin-bottom: 0;
    text-align: center;

    color: #707070;
}

#app {
    font-family: 'Roboto', sans-serif;

    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;

    width: 100vw;
    margin: 0;

    overflow-x: hidden;
}

/* a {
    position: relative;
    color: black;
    text-decoration: none;

    &::after {
        content: "";
        position: absolute;
        z-index: -1;
        top: 70% !important;
        left: -0.1px;
        right: -0.1px;
        bottom: 0;
        transition: top 0.1s ease-in-out;
        background-color: rgba(76,131,255, 0.5);
    }

    &:hover::after {
        top: 0;
    }
} */
</style>
