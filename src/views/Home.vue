<template>
<div class="home">
  <header>
    <div class="text">
      <h1>Glarce</h1>
      <p>Web AR, simplified</p>
    </div>

    <div class="wave"></div>
  </header>

  <div class="features">
    <div class="feature" id="simple">
      <h2>Simple but Powerful</h2>

      <div class="simpleFetures">
        <div class="blob">
          <span class="text"><p>Set up in minutes not hours</p></span>
        </div>
        <div class="blob two">
          <span class="text"><p>Shields you from browser suport and low level code</p></span>
        </div>
        <div class="blob">
          <span class="text"><p>Writen for the web</p></span>
        </div>
        <div class="blob two">
          <span class="text"><p>Modular</p></span>
        </div>
        <div class="blob">
          <span class="text"><p>Advanced 3D with a-frame</p></span>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
// @ is an alias to /src

export default
{
	name: 'home',
	components:
  {

  }
}
</script>

<style scoped lang="scss">
@import "../styles/home";
</style>
