<template>
  <div id="app">
   <h1>{{ message }}</h1> 
    <contador></contador>
  </div>
</template>

<script>
import Contador from "./componentes/Contador.vue"
  export default {
    data() {
      return {
        message: 'Cuenta atrás',
      };
    },
    components: {Contador},
    methods:{

    }
  }
</script>

<style scoped>
 
</style>