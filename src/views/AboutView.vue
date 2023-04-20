<script setup>
let user = "daniel";
</script>
<template>

  <h1 class="Welcome">{{ user }}</h1>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
