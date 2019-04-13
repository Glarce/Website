<template>
<nav>
  <a href="/Docs" class="link">Docs</a>
  <a href="/Glarce" class="link">Demo</a>

  <!-- <router-link to="/">Home</router-link>
  <router-link to="/about">About</router-link> -->
</nav>
</template>

<script>
export default
{
  name: 'navbar'
}
</script>

<style lang="scss" scoped>
nav {
    padding: 10pt;

    position: absolute;
    left: 0;
    top: 0;

    display: flex;

    .link {
        padding: 10px;

        color: #fff;
        text-decoration: none;

        transition-duration: 0.1s;

        &:hover {
            color: #aaa;
        }
    }
}
</style>
