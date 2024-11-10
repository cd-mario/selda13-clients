<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from '../src/components/Header.vue'
</script>

<template>
  <div class="container">
    <Header />
    <RouterView />
  </div>
</template>

