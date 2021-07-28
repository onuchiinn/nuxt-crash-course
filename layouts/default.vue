<template>
  <div>
    <Navbar />

    <main>
      <div class="container">
        <Nuxt />
      </div>
    </main>
  </div>
</template>

<script>

import Navbar from '../components/Navbar'

export default {
  name: "default",
  components: {
    Navbar
  }
}
</script>

<style scoped>

</style>
