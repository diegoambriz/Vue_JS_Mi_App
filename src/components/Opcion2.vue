<template>
  <div class="card col-md-4">
    <div class="card-body">
      <h5 class="card-title">Opcion 2 - {{entradaDeTexto}}</h5>
      <!-- <form> -->
      <p
        class="card-text"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>

      <!-- <div class="row"> -->
      <!-- One Way Binding <input v-bind:value="entradaDeTexto" /> -->
      <input v-model="entradaDeTexto" />
      <br />

      <!-- </div> -->
      <!-- <div class="row"> -->
      <a class="btn btn-secondary" v-on:click="entradaDeTexto = 'NUEVO VALOR'">Opcion 2</a>
      <!-- </div> -->
      <!-- </form> -->
    </div>
  </div>
</template>

<script>
export default {
  name: "Opcion2",
  data() {
    return {
      entradaDeTexto: "*** Texto ***"
    };
  }
};
</script>

<style>
</style>
