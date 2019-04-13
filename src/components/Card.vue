<template>
<div class="card">
  <p v-if="title" class="title" v-html="title"></p>

  <slot></slot>
</div>
</template>

<script>
export default
{
  name: 'card',
  props: ['title']
}
</script>

<style lang="scss">
.card {
    border-radius: 2px;
    padding: 5px;
    margin: 5px;

    -webkit-box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);
    -moz-box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);
    box-shadow: 2px 2px 6px 0 rgba(0,0,0,0.25);

    .title {
        font-size: 0.0625rem * 2;
    }
}
</style>
