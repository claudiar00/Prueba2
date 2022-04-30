<script>
export default {
  data() {
    return {
      message: ''
    }
  }
}
</script>

<template>
	<p>Message is: {Welcome to Global Terrorism Database} </p>
	<input v-model="message" placeholder="edíteme">
	<p>El mensaje es: {{ message }}</p>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>


