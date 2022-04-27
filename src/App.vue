
<template>
  <div>Hola {{ value }}</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "Pedazo de cerdas"
    };
  };
  
<h2>Select</h2>
  <select v-model="selected">
    <option disabled value="">Please select the country you want:</option>
    <option>Irak</option>
    <option>Spain</option>
    <option>India</option>
  </select>
  <span>Selected: {{ selected }}</span>
  </script>
};

