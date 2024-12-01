<template>
    <div class="child">
      <input 
        v-model="message" 
        type="text" 
        placeholder="Escribe un mensaje"
      >
      <button @click="sendMessage">Enviar mensaje</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Child',
    data() {
      return {
        message: ''
      }
    },
    methods: {
      sendMessage() {
        this.$emit('send-message', this.message)
        this.message = ''
      }
    }
  }
  </script>