
<script setup>

   new Vue({
      el: '#app',
      data: {
        usuarios: [
          { nombre: 'Ana', apellido: 'Pérez', fechaNacimiento: '1990-05-12', edad: 35 },
          { nombre: 'Luis', apellido: 'Gómez', fechaNacimiento: '1985-11-23', edad: 39 },
          { nombre: 'Carla', apellido: 'Ramírez', fechaNacimiento: '2000-01-08', edad: 25 }
        ]
      }
    });
</script>

<template>
 <h2 class="mb-4">Usuarios Registrados</h2>
 <table class="table table-bordered table-striped">
      <thead class="thead-dark">
        <tr>
          <th>Nombre</th>
          <th>Apellido</th>
          <th>Fecha de Nacimiento</th>
          <th>Edad</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="usuario in usuarios" :key="usuario.nombre">
          <td>{{ usuario.nombre }}</td>
          <td>{{ usuario.apellido }}</td>
          <td>{{ usuario.fechaNacimiento }}</td>
          <td>{{ usuario.edad }}</td>
        </tr>
      </tbody>
    </table>

</template>


