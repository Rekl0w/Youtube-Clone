<script setup>
import Navbar from "./components/NavBar.vue";
import Topbar from "./components/TopBar.vue";
import Videos from "./components/Videos.vue";
</script>

<template>
  <div class="bg-black overflow-x-hidden overflow-y-visible min-h-screen hm">
    <Topbar />
    <Navbar/>
    <Videos />
  </div>
</template>

<style scoped>

.hm::-webkit-scrollbar {
  width: 8px;
}

.hm::-webkit-scrollbar-track {
  background-color: #f1f1f1;
}

.hm::-webkit-scrollbar-thumb {
  background-color: #888;
  border-radius: 4px;
}

.hm::-webkit-scrollbar-thumb:hover {
  background-color: #555;
}

</style>