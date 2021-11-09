<template>
  <div >
  
    <div class="modal">
  <div class="modal-background"></div>
  <div class="modal-content">
    <!-- Any other Bulma elements you want -->
  </div>
  <button class="modal-close is-large" aria-label="close"></button>
</div>

  </div>
</template>

<script>

import navigation from './components/Navigation.vue';

export default {
  name: 'App',
  components: {
    navigation,
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
