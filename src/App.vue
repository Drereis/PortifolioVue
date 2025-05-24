<script setup>
import Navbar from "./components/NavbarComponent.vue";
</script>
<template>
  <div id="Body">
    <Navbar />
    <div class="container mx-auto px-4 py-6">
      <router-view></router-view>
    </div>
  </div>
</template>
<script setup></script>
<style>
#Body {
  background: linear-gradient(-70deg, #3e035a9d, #3b38e6, #2370d5, #073791);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
  height: 100vh;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>
