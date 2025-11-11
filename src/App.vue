<template>
  <div class="container"h1>
    <Header />
    <Home />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home
  }
}
</script>

<style>
.container {
  max-width: 1200px; /* ou 100%, se quiser ocupar tudo */
  margin: 0 auto;
  padding: 0 20px;
}
</style>