<template>
  <div class="page">
    <h1>Contact</h1>
    <p><strong>Name:</strong> Kenzie Langston</p>
    <p><strong>Email:</strong> <a href="mailto:mnlangston1@my.waketech.edu">mnlangston1@my.waketech.edu</a></p>
    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from '../components/GoBackButton.vue'

export default {
  name: 'Contact',
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
