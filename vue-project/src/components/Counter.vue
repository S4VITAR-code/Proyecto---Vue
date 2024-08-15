<template>
<h1>
  Hello World
</h1>

<button @click="incrementCounter">Increment {{ counter }}</button>
<button @click="decrementCounter">Decrement</button>
</template>

<script setup>
import { ref } from 'vue'; //Para declarar un estado Reactivo se utlizar ref()

const counter = ref(0);

const incrementCounter = () => {
  counter.value++;
}

const decrementCounter = () => {
  counter.value--;
}
</script>

<style scoped>

</style>