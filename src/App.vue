<template>
 <Header/>
  <Main/>
  <div class="flex">
    <Cards/>
    <Order/>
  </div>
</template>
<script setup>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Cards from "./components/Cards.vue";
import Order from './components/Order.vue'
</script>