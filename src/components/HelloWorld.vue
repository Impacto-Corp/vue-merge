<script setup>

</script>

<template>
  <h1>contenedor izquierdo</h1>
  <h1>Raul</h1>
  <h1>Primera modificacion Raul</h1>
  <h1>2da modificacion Raul</h1>
  <h1>3era modificacion Raul</h1>
  <h1>4ta modificacion Raul</h1>
</template>

<style scoped>
h1 {
  font-weight: 500;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
