<script setup>
// import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="nav">
    <HelloWorld msg="You did it!" />
    <!-- <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->
  </div>
  <!-- <RouterView /> -->
</template>

<style scoped>
* {
  padding: 0;
  margin: 0;
}

.nav {
  width: 100%;
  height: 64px;
  border: 1px solid black;
}
</style>
