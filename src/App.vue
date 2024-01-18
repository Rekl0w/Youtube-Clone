<script setup>
import Navbar from "./components/NavBar.vue";
import Topbar from "./components/TopBar.vue";
import Filters from "./components/Filters.vue";
</script>

<template>
  <div class="bg-black overflow-hidden max-h-screen">
    <Topbar />
    <Filters />
    <Navbar />
  </div>
</template>

<style scoped></style>
