<template>
  <h1>let's go</h1>
  <resume />
</template>

<script>
import resume from './src/components/resume.vue'

export default {
  name: 'App',
  components: {
    resume
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
