<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <div class="card">
    <h1>La mia prima APP con Vite ☝</h1>
    <button type="button" @click="count++">Clicca sul mio Contatore {{ count }}</button>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
