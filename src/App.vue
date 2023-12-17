<template>
  <ContainerEl><ChatMessage datatime="sd" name="sd">Привет!</ChatMessage></ContainerEl>
</template>

<script>
import ContainerEl from './components/Container.vue'
import ChatMessage from './components/ChatMessage.vue'


export default {
  name: 'App',
  components: {
    ContainerEl,
    ChatMessage
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
</style>
