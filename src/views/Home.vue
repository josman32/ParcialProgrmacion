<template>
  <div class="home h-screen bg-gray-500 text-white" align="center">
    <img width="400" height="400" alt="Manuel Alumno" src="../assets/manuelAR.jpg">
    <br>
    <Presentacion msg="Jose Manuel Mejia"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Presentacion from '@/components/Presentacion.vue'

export default {
  name: 'Home',
  components: {
    Presentacion
  }
}
</script>
