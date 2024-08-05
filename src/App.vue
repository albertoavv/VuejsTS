<template>
  <div>
    <Formulario />
   <Boton nombre = "Enviar" disabled clase="success" />
   <Boton type="submit" nombre = "Eliminar" clase="danger" />
   <Boton type="submit" nombre = "Cuidado" clase="warning" />
  </div>
</template>

<script setup lang="ts">
//import BotonContador from './components/BotonContador.vue';
import Boton from './components/Boton.vue';
import Formulario from './components/Formulario.vue';

</script>

<style scoped>

</style>