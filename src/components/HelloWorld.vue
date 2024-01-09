<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <img src="/assets/images/Profile Picture.jpg">
  <h1>{{ msg }}</h1>
  <h2>Jado ma bug lai liyera ghar pharkhandai. 😂😂😂 Comming Soon !</h2>
</template>

<style scoped>

</style>
