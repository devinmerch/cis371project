<template>
  <Navbar :icon="icon" :cart="cart" />
  <hr />
  <RouterView></RouterView>
</template>



<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import Chart from './components/Chart.vue';
import icon from './assets/icon.png';
import cart from './assets/cart.png';
import { useRouter } from "vue-router";




</script>

<style>
body {
  font-family: 'Comfortaa', cursive;
}
</style>
