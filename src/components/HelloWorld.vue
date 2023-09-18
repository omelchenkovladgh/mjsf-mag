<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    121 Програмна інженерія, 2 курс (м)
  </p>
  <p>
   8.1212
  </p>
  <p class="read-the-docs">Омельченко В.О.</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
