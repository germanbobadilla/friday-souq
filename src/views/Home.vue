<template>
  <div class="home p-10">
    <Navbar />
    <header class=" py-10 text-center flex justify-center">
      <div class="shadow p-10 rounded">
      <h1 class="text-4xl">Hi!</h1>
      <h2 class="text-2xl text-gray-600">Welcome to Friday Souq</h2>
      </div>
    </header>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
