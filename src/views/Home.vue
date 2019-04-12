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
    <div class="feature" id="web">
      <h2>Web based</h2>

      <div class="top">
        <p>Designed and made on the web, for the web</p>
        <img src="../assets/04.png">
      </div>

      <div class="middle">
        <p>Available on everything with connection</p>
        <img src="../assets/iphone-x.svg">
      </div>

      <div class="bottom">
        <p><a class="borderMarker" href="https://glarce.github.io/Glarce/">Try it out right now, here in the browser!</a></p>
        <img src="../assets/05.png">
      </div>
    </div>

    <div class="feature" id="simple">
      <h2>Simple Yet Powerful</h2>
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
