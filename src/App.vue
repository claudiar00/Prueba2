<template>
  <div>Hola {{ value }}</div>
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

<p>Nombre: <input type="text" name="nombre" required></p>
