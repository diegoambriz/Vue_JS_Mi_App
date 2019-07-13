<template>
  <li class="navbar-brand">
    <a class="navbar-brand" v-bind:href="navegacionData.url">{{navegacionData.titulo}}</a>
  </li>
</template>

<script>
export default {
  name: "NavegacionItem",
  data() {
    return {};
  },
  props: {
    navegacionData: Object
  }
};
</script>

<style>
</style>
