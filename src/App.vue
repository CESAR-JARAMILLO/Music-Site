<template>
  <div>
    <Navbar />
    <Hero />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Hero from './components/Hero'

export default {
  name: 'App',
  components: {
    Navbar,
    Hero
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
