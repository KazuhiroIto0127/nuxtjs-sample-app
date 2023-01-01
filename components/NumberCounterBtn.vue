<script setup>
const counter = useState('counter', () => Math.round(Math.random() * 1000))
</script>

<template>
  <div>
    <button @click="counter++" class="border-2 border-gray-500 rounded-md p-2 m-2">＋</button>
    <button @click="counter--" class="border-2 border-gray-500 rounded-md p-2 m-2">ー</button>
    Counter: {{ counter }}
  </div>
</template>
