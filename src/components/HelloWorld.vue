<script setup lang="ts">
defineProps<{
  msg: string
}>();
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      You’ve successfully created a project with
      <a href="https://cn.vitejs.dev/" target="_blank" rel="noopener">Vite</a> +
      <a href="https://cn.vuejs.org/" target="_blank" rel="noopener">Vue 3</a> +
      <a href="https://pinia.vuejs.org/zh/" target="_blank" rel="noopener">Pinia</a> +
      <a href="https://router.vuejs.org/zh/" target="_blank" rel="noopener">Vue Router</a> +
      <a href="https://www.typescriptlang.org/zh/" target="_blank" rel="noopener">TypeScript</a> +. What's next?
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
