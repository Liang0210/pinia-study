<script setup>
import {useCounterStore} from '../stores/counter';
const countStore=useCounterStore()
</script>
<template>
  <div class="about">
  <h1>count : {{ countStore.count }}</h1>
  <h1>2*count: {{ countStore.doubleCount }}</h1>
  <button @click="countStore.increment()">increment</button>
  </div>
</template>

<style>

</style>
