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
          <span class="text">
            <p>Set up in minutes not hours</p>
          </span>
        </div>
        <div class="blob two">
          <span class="text">
            <p>Shields you from browser suport and low level code</p>
          </span>
        </div>
        <div class="blob">
          <span class="text">
            <p>Writen for the web</p>
          </span>
        </div>
        <div class="blob two">
          <span class="text">
            <p>Modular</p>
          </span>
        </div>
        <div class="blob">
          <span class="text">
            <p>Advanced 3D with a-frame</p>
          </span>
        </div>
      </div>
    </div>

    <div class="feature" id="docs">
      <h2>Well documened</h2>

      <div class="docs-grid">
        <div class="left">
          <p>Everything you need to know, from installation to deployment in one place</p>
        </div>

        <div class="right">
          <a href="/Docs/guide/">
            <card>
              <a>Getting started</a>
            </card>
          </a>
          <a href="/Docs/API/">
            <card>
              <a>API</a>
            </card>
          </a>
          <!-- <card><a>Deployment</a></card> -->
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue'

export default
{
  name: 'home',
  components:
  {
    Card
  }
}
</script>

<style scoped lang="scss">
@import "../styles/home";
</style>

<style lang="scss">
#app {
    background: rgb(42,250,223);
    background: linear-gradient(210deg, rgba(42,250,223,1) 0%, rgba(76,131,255,1) 100%);
}
</style>
