<template>
  <ul class="navbar navbar-expand-lg navbar-dark bg-dark">
    <NavegacionItem v-bind:navegacionData="item" v-for="item in itemsDeNavegacion" />
  </ul>
</template>

<script>
import NavegacionItem from "./NavegacionItem.vue";

export default {
  name: "Navegacion",
  components: {
    NavegacionItem
  },
  data() {
    return {
      itemsDeNavegacion: [
        { titulo: "Inicio", url: "/home" },
        { titulo: "Acerca De", url: "/about" },
        { titulo: "Tienda", url: "/tienda" },
        { titulo: "Contacto", url: "/contacto" },
        { titulo: "Mapa", url: "mapa" }
      ]
    };
  }
};
</script>

<style>
</style>
