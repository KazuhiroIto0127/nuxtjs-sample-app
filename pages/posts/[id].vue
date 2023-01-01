<script setup>
const route = useRoute()
const counter = useState('counter', () => Math.round(Math.random() * 1000))
</script>

<template>
  <section>
    <p>post page</p>
    <p>{{route.params.id}}</p>
  </section>
</template>
