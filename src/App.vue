<template>
  <ion-app>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Home/>
  </ion-app>
</template>

<script>
import { IonApp } from '@ionic/vue';

import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    IonApp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
