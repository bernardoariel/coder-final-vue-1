<template>
  <div id="app">
   <login-component></login-component>
   <register-component></register-component>
   <productos-component></productos-component>
   <producto-component></producto-component>
   <lista-productos-cards></lista-productos-cards>
  </div>
</template>

<script>
import LoginComponent from './components/LoginComponent.vue'
import RegisterComponent from './components/RegisterComponent.vue';
import ProductosComponent from './components/ProductosComponent.vue'
import ProductoComponent from './components/ProductoComponent.vue';
import ListaProductosCards from './components/ListaProductosCards.vue';
export default {
  name: 'App',
  components: {
    LoginComponent,
    RegisterComponent,
    ProductosComponent,
    ProductoComponent,
    ListaProductosCards
    
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
