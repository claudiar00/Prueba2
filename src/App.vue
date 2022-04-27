<template>
  <div>Hola {{ value }}</div>
  <p>Nombre: <input type="text" name="nombre" required></p>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "cla EDITANDO 2"
    };
  }
};
</script>


