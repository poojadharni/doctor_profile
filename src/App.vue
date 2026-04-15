<template>
  <div>

    <!-- Navbar -->
    <Navbar />

    <!-- Page Content -->
    <router-view />

    <!-- Footer -->
    <Footer />

  </div>
</template>

<script>
import Navbar from "./pages/NavBar.vue"
import Footer from "./pages/Footer.vue"

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>