<script setup>
import MyName from './components/MyName.vue'
</script>

<template>
  <main class="page-shell">
    <section class="welcome-panel">
      <p class="eyebrow">FIT5032 Assessed Lab 1</p>
      <h1>Welcome to my VueJS app</h1>
      <p class="intro">
        This page is running locally with Vue and Vite for eFolio Task 1.1 and
        includes a custom component for Task 1.2.
      </p>

      <MyName />
    </section>
  </main>
</template>
