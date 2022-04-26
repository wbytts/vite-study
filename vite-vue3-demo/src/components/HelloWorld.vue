<script setup>
let msg = 'Hello World';

function handleClick() {
  console.log('点击了按钮123');
}
</script>

<template>
  <div>{{ msg }}</div>
  <button @click="handleClick">按钮</button>
</template>

<style scoped></style>
