<template>
  <div class="card col-md-4">
    <div class="card-body">
      <h5 class="card-title">Opcion 3 {{estado}}</h5>
      <p
        class="card-text"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
      <input @keypress="estado='Tecla Presionada'" @keypress.enter="estado='Tecla EnterPresionada'" />
      <br />
      <a
        v-on:click="estado='Mouse Click'"
        v-on:mouseover="estado='Mouse Over'"
        class="btn btn-success"
      >Opcion 3</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Opcion3",
  data() {
    return {
      estado: ""
    };
  }
};
</script>

<style>
</style>
