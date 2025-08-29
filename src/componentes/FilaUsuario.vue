<template>
  <tr>
    <td>{{ usuario.nombre }}</td>
    <td>{{ usuario.apellido }}</td>
    <td>{{ usuario.fechaNacimiento }}</td>
    <td>{{ usuario.edad }}</td>
  </tr>
</template>

<script>
export default {
  props: ['usuario']
}
</script>
