<template>
  <div>
    <div class="jumbotron">
      <h1 class="display-4">Vue.JS</h1>
    </div>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

    <div class="row">
      <Opcion1 />
      <Opcion2 />
      <Opcion3 />
    </div>
  </div>
</template>

<script>
import Opcion1 from "./Opcion1.vue";
import Opcion2 from "./Opcion2.vue";
import Opcion3 from "./Opcion3.vue";

export default {
  name: "Contenido",
  components: {
    Opcion1,
    Opcion2,
    Opcion3
  }
};
</script>

<style>
</style>
