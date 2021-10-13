<template>
  <header>
    <h2>Hola mundo</h2>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <p v-if="myVariable">Hola a todos!</p>
    <p>Nombre: {{ name }} {{ lastname }}</p>
    <p>Edad: {{ age }}</p>
    <input v-model="job" placeholder="Trabajo" />
    <hr />

    <div>
      <input type="checkbox" v-model="myVariable" />
      <label>Mostrar mensaje</label>
    </div>
    <hr />
    <p>Trabajo ingresado: {{ job }}</p>
  </header>
</template>

<script>
export default {
  name: "Header",
  data: function () {
    return {
      myVariable: false,
      name: "Carlos",
      age: 26,
      lastname: "Gomez",
      job: "",
    };
  },
};
</script>

<style scoped>
#nav {
  background: rgb(151, 176, 243);
}
</style>
