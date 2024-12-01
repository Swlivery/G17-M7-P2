<template>
    <div class="parent">
      <h2>Ejercicio 3 - Comunicación entre componentes</h2>
      <p>Mensaje recibido: {{ receivedMessage }}</p>
      <Child @send-message="handleMessage" />
    </div>
  </template>
  
  <script>
  import Child from '../Child/Child.vue'
  
  export default {
    name: 'Parent',
    components: {
      Child
    },
    data() {
      return {
        receivedMessage: ''
      }
    },
    methods: {
      handleMessage(message) {
        this.receivedMessage = message
      }
    }
  }
  </script>