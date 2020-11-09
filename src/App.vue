<template>
  <div id="app">
    <Main />
  </div>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Main
  }
}
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Hind&display=swap');
  #app {
    font-family: Hind;
    font-weight: 400;
    text-transform: none;
    color: #424242;
    line-height: 1.42857143;
    font-size: 1rem;
  }
</style>
