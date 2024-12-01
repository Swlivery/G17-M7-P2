<template>
    <div class="counter">
      <h2>Ejercicio 1 - Counter con Vuex</h2>
      <div class="counter-display">
        <p>Contador: {{ counter }}</p>
      </div>
      <div class="counter-controls">
        <button @click="increment">Incrementar</button>
        <button @click="decrement">Decrementar</button>
      </div>
    </div>
  </template>
  
  <script>
  import { mapGetters, mapActions } from 'vuex'
  
  export default {
    name: 'Counter',
    computed: {
      ...mapGetters(['getCounter']),
      counter() {
        return this.getCounter
      }
    },
    methods: {
      ...mapActions(['increment', 'decrement'])
    }
  }
  </script>
  
  <style scoped>
  .counter {
    padding: 20px;
    text-align: center;
  }
  .counter-display {
    font-size: 24px;
    margin: 20px 0;
  }
  .counter-controls button {
    margin: 0 10px;
    padding: 10px 20px;
    font-size: 16px;
  }
  </style>