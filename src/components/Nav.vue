<template>
<nav>
  <router-link to="/">Home</router-link>
  <router-link to="/about">About</router-link>
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
}

a {
    padding: 5pt;

    color: #fff;
    text-decoration: none;
}
</style>
