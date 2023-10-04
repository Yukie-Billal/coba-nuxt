<script setup>
import './assets/app.css'
import Main from './components/Main.vue'
const message = "Hello, Yukie muhammad billal"
</script>
<template>
  <div>
      <Main :message="message" />
  </div>
</template>

<style scoped>
div {
   height: 100vh;
   display: flex;
   justify-content: center;
   align-items: center;
   background: #171616;
}
</style>