<script>
export default {
  data() {
    return {
      titleClass: 'title'
      text: ''
    }
  }
}
</script>

<template>
  <h1 :class="titleClass">Massive Data project</h1>
  <h2> This is a project developed by miriam, clau, esther,ire, and elena </h2>
  <input v-model="text" placeholder="Type here">
  <p>{{ text }}</p>
</template>

<style>
.title {
  color: blue;
}
