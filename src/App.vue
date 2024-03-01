<template>
  <nav class="navbar navbar-expand navbar-light bg-light">
    <div class="nav navbar-nav">
      <router-link to="/CrearItem" class="nav-link">Crear</router-link>
      <router-link to="/ListarItem" class="nav-link">Empleados</router-link>
    </div>
  </nav>
  <br />
  <router-view />
</template>
