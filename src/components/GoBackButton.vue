<template>
  <button class="go-back" @click="goBack">← Go Back</button>
</template>

<script>
import { useRouter } from 'vue-router'

export default {
  name: 'GoBackButton',
  setup() {
    const router = useRouter()
    const goBack = () => router.back()
    return { goBack }
  }
}
</script>

<style scoped>
.go-back {
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  font-size: 1rem;
  cursor: pointer;
  border: 1px solid #2c3e50;
  background: #fff;
  border-radius: 4px;
}
.go-back:hover {
  background: #2c3e50;
  color: #fff;
}
</style>
