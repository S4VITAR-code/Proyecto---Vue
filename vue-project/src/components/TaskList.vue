<template>
<div>
  <h2>To-Do List</h2>
  <input type="text">
  <ul>
    <li>Task</li>
  </ul>
</div>
</template>

<script setup>
import { ref } from 'vue';

const tasks = ref([]);
const newTask = ref('');
</script>

<style scoped>

</style>