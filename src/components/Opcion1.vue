<template>
  <div class="card col-md-4">
    <div class="card-body">
      <h5 class="card-title">{{texto}}</h5>
      <p
        class="card-text"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
      <button class="btn btn-primary" v-on:click="letraElegida('A')">Boton A</button>
      <br />
      <br />
      <button class="btn btn-primary" v-on:click="letraElegida('B')">Boton B</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Opcion1",
  data() {
    return {
      opcion: "",
      texto: "Titular"
    };
  },
  methods: {
    sumar: function() {
      this.opcion = Math.floor(Math.random() * 1000);
    },
    letraElegida: function(letra) {
      this.texto = "SELECCIONASTE EL BOTON " + letra;
    }
  }
};
</script>

<style>
</style>
