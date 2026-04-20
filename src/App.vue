
<template>
  <div class="min-h-screen bg-gray-100 flex flex-col items-center justify-center gap-4">
    <h1 class="text-3xl font-bold text-gray-800">Vue js 입니다.</h1>
    <div class="flex gap-2">
      <button class="bg-blue-500 text-white font-bold px-4 py-2 rounded hover:bg-blue-600" @click="count++">Count Plus</button>
      <button class="bg-red-500 text-white font-bold px-4 py-2 rounded hover:bg-red-600" @click="count--">Count Minus</button>
    </div>
    <div class="text-2xl font-semibold text-gray-700">{{ count }}</div>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>
