<script setup>
defineProps({
  name: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ name }}</h1>
    <h3>
      my github link is 
      <a href="https://github.com/xlii0342" target="_blank" rel="noopener">Vite</a>.
    </h3>
  </div>
</template>