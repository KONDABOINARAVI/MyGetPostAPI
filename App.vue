<template>
  <h2 class=""Underline>"Underline"</h2>
</template>

<script> 
import CreatePost from './components/CreatePost.vue'


export default {
  name: 'App',
  components: { 
  },
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
.underline{
  text-decoration: underline;
}
</style>