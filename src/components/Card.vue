<template>
<a :href="link" class="card">
  <p v-if="title" class="title" v-html="title"></p>

  <slot></slot>
</a>
</template>

<script>
export default
{
  name: 'card',
  props: ['title', 'link']
}
</script>

<style lang="scss">
.card {
    color: black;
    text-decoration: none !important;
    border-radius: 3px;
    border-style: solid;
    border-width: 1px;
    border-color: rgba(5,5,5,0);
    padding: 5px;
    margin: 5px;
    transition-duration: 0.2s;

    -webkit-box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);
    -moz-box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);
    box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);

    .title {
        font-size: 0.0625rem * 2;
    }

    &:hover {
        border-color: rgba(76,131,255, 0.5);
    }
}

a {
    color: inherit;
    text-decoration: none !important;
}
</style>
