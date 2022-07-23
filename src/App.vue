<template>
  <main>
    <Navbar />
    <Showcase />
    <InfoSection />
    <Articles />
    <Footer />
  </main>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Showcase from './components/Showcase.vue'
import InfoSection from './components/InfoSection.vue'
import Articles from './components/Articles.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Showcase,
    InfoSection,
    Articles,
    Footer
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

.container {
  width: 1100px;
  margin: 0 auto;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.btn {
  color: white;
  border: none;
  background-image: linear-gradient(to right, hsl(136, 65%, 51%), hsl(192, 70%, 51%));
  padding: 10px 22px;
  border-radius: 50px;
}

@media only screen and (max-width: 375px) {
  .container {
    width: 80%;
  }
  html, body {
    width: 100%;
  }
}
</style>
