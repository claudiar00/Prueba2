<script>

message = 'Welcome to Global Terrorism Database!'
intro = 'Please select a country to check their terrorism statistics:'
Selected = ''
</script>

<template>
  <h1>{{ message }}</h1>
  <h5>{{intro}}</h5>
  <select v-model="Selected">
    <option disabled value="">Please select one</option>
    <option>Iraq</option>
    <option>India</option>
    <option>Spain</option>
  </select>
  <br>
  <br>
  <span>The country selected is: {{ Selected }}</span>
</template>
