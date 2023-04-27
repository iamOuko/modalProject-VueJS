<template>
  <h1>{{ title }}</h1>
  <Modal :header="header" :text="text" theme="sale"/>
  
</template>

<script>
import Modal from './components/Modal.vue'

export default {
  name: 'App',
  components: { Modal },
  data() {
    return {
      title: 'vue app',
      header: 'Sign up for giveaway!',
      text: 'Grab your swag for half price'
    }
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
