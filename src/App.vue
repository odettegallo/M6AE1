<script setup></script>

<template>
  <div class="container mt-5">
    <h2>Usuarios Registrados</h2>
    <TablaUsuarios />
  </div>
</template>

<script>
import TablaUsuarios from './components/TablaUsuarios.vue'

export default {
  components: {
    TablaUsuarios,
    FilaUsuario
  }
}
</script>


<style scoped></style>
