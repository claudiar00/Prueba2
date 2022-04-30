<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>

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
  <button @click="count++">Count is: {{ count }}</button>
</template>

<template>
  <p>Message is: {Hola}</p>
	<input v-model="message" placeholder="edit me"</input>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>


