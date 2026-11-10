<template>
  <div class="page">
    <h1>About</h1>
    <p>
      This page is part of the Module 11 assignment for WEB 125.
      It demonstrates client-side routing with Vue Router 4, including
      navigation links, a "Go Back" button, and a not found router component.
    </p>
    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from '../components/GoBackButton.vue'

export default {
  name: 'About',
  components: { GoBackButton }
}
</script>

<style scoped>
.page {
  max-width: 720px;
  margin: 2rem auto;
  padding: 0 1rem;
  text-align: left;
}
</style>
