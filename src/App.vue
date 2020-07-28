<template>
  <div id="app">
    <myName />
  </div>
</template>

<script>
import myName from './components/myName.vue'

export default {
  name: 'App',
  components: {
    myName
  }
}
</script>

<style>
    * {
      margin:0;
      padding:0;
      box-sizing: border-box;
    }
</style>
