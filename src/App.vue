<template>
  <h1>{{ title }}</h1>
  <Modal :header=header :text=text theme="sale"/>
</template>

<script>
import Modal from './components/Modal.vue'

export default {
  name: 'App',
  data() {
    return {
      title: 'Final Modal Title',
      header: "On Sale Now!",
      text: "Get Your Today"
    }
  },
  components: { Modal }
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
