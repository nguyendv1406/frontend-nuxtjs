<template>
  <div>TEST - data: {{ data }}</div>
</template>

<script setup lang="ts">
const { data, error } = await useFetch(`http://localhost:3010/`);

console.log(data, 3333333333);
</script>

<style scoped></style>
