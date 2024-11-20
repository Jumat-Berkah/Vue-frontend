<template>
  <div>
    <Navbar />
  </div>
  <RouterView />
</template>

<script>
import { RouterView } from "vue-router";
import Navbar from "./components/Navbar.vue";
</script>

<style scoped></style>
