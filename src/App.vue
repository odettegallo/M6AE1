<script setup></script>

<template>
  <div class="container mt-5">
    <h2>Usuarios Registrados</h2>
    <TablaUsuarios />
  </div>
</template>

<script>
import TablaUsuarios from './components/TablaUsuarios.vue'
import FilaUsuario from './components/FilaUsuarios.vue'

export default {
  components: {
    TablaUsuarios,
    FilaUsuario
  }
}
</script>


<style scoped></style>
