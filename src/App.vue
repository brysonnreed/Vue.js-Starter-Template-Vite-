<template>
  <!-- Delete -->
  <h1>
    <span>{{ framework }}</span> Base Starter With <span>{{ bundler }}</span>
  </h1>
  <a
    href="https://github.com/brysonnreed?tab=repositories"
    target="_blank"
    aria-label="Link to my other Github repositories"
    class="btn"
    >My Github Repos
  </a>
  <!-- Delete -->
</template>

<script setup>
import "./assets/main.css";
const framework = "Vue.js";
const bundler = "Vite";
</script>
