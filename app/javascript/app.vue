<template>
  <div class="container text-center mt-5">
    <div class="row">
      <div class="col-md-12">

        <div id="app">
          <h1>{{ titulo }}</h1>

          <!-- Componente Postres -->
          <Postres/>

        </div>

      </div>
    </div>
  </div>
</template>

<script>

  // Importo el componente 'Postres' 
  import Postres from './Postres'

  export default {

    // Defino el componente 'Postres' 
    components: {
      Postres,
    },

    data: function () {
      return {
        titulo: "Lista de Postres"
      }
    }

  }
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
