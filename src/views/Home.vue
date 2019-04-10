<template>
<div class="home">
  <header>
    <div class="text">
      <h1>Glarce</h1>
      <p>Web AR, simplified</p>
    </div>
  </header>

  <div class="features">
    <div>

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
@import url('https://fonts.googleapis.com/css?family=Quicksand');

header {
    height: 102vh;
    background: rgb(42,250,223);
    background: linear-gradient(210deg, rgba(42,250,223,1) 0%, rgba(76,131,255,1) 100%);

    color: #eee;
    font-family: 'Quicksand', sans-serif;

    border-bottom-left-radius: 50% 2vh;
    border-bottom-right-radius: 50% 2vh;

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

.features {
  height: 100vh;
}
</style>
