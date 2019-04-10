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

      <p>Desigend and made on the web, for the web</p>
      <p>Available on everything with connecton</p>
      <p><a class="borderMarker" href="https://glarce.github.io/Glarce/">Try it out right now, here in the browser!</a></p>
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
@import url('https://fonts.googleapis.com/css?family=Overpass');

header {
    height: 100vh;
    background: rgb(42,250,223);
    background: linear-gradient(210deg, rgba(42,250,223,1) 0%, rgba(76,131,255,1) 100%);

    color: #eee;

    font-family: 'Overpass', sans-serif !important;

    .wave {
        background-image: url("../assets/white-split.svg");
        background-repeat: no-repeat;
        background-size: cover;

        position: absolute;
        bottom: -1px;

        height: 10%;
        width: 100%;
    }

    .text {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);

        h1 {
            font-size: 96pt;
            margin: 0;
        }
        p {
            font-size: 20pt;
            margin: 0;
        }
    }
}

.features {}

.borderMarker {
    position: relative;

    color: black;
    text-decoration: none;
}

.borderMarker::after {
    content: "";
    position: absolute;
    z-index: -1;
    top: 70%;
    left: -0.1px;
    right: -0.1px;
    bottom: 0;
    transition: top 0.1s ease-in-out;
    background-color: rgba(76,131,255, 0.5);
}

.borderMarker:hover::after {
    top: 0;
}
</style>
