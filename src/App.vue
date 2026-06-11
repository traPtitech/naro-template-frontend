<script setup lang="ts">
import ClickCounter from './components/ClickCounter.vue'
import WelcomeMessage from './components/WelcomeMessage.vue'
</script>

<template>
  <main>
    <WelcomeMessage msg="Webエンジニアになろう講習会へようこそ" />
    <ClickCounter />
  </main>
</template>

<style scoped>
main {
  padding: 2rem;
}
</style>
