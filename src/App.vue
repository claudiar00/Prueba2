<template>
  <div>Hola {{ value }}</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: <p>Nombre: <input type="text" name="nombre" required></p>
    };
  }
};
</script>


