<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img alt="Vue logo" class="myclass" src="./assets/logo.png" />
  <div class="pb-14 bg-blue-400 myclass">
    <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.myclass {
  outline: 1px solid red;
}
</style>


