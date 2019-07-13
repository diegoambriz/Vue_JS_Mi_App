<template>
  <div id="app">
    <Navegacion />
    <div class="container">
      <div class="row">
        <Contenido />
      </div>
    </div>
  </div>
</template>

<script>
import Navegacion from "./components/Navegacion.vue";
import Contenido from "./components/Contenido.vue";

export default {
  name: "app",
  components: {
    Navegacion,
    Contenido
  }
};
</script>

<style>
</style>
