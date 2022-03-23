<template>
  <div class="w-screen h-screen bg-primary flex items-center justify-center">
    <div class="container flex items-center justify-center">
    <login></login>
    </div>
  </div>
</template>

<script>
import Login from '@/components/Login.vue'
export default {
  name: "index",
  components: {
    Login
  }
}
</script>

<style scoped>

</style>