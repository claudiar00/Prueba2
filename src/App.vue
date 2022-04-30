
<script setup>
import { ref } from 'vue'

const message = ref('Welcome to Global Terrorism Database!')
const intro = ('Please select a country to check their terrorism statistics:')
const selected = ref('')
const graphs = ('The statistics of a terrorism attack in the selected country are listed below: ')
</script>

<template>
  <h1>{{ message }}</h1>
  
  <h5>{{intro}}</h5>

  <select v-model="selected">
    <option disabled value="">Please select one</option>
    <option>Iraq</option>
    <option>India</option>
    <option>Spain</option>
  </select>
  <br>
  <br>
  <span>The country selected is: {{ selected }}</span>
  <br>
  <br>

  <h8>{{graphs}}</h8>
</template>
