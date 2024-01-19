<script setup>
import { ref } from "vue";

const videos = ref([
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 2",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 2",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 3",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 2",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 2",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
  {
    id: 1,
    title: "Video 1",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/user.png",
  },
  {
    id: 2,
    title: "Video 2",
    description: "Bu bir video açıklamasıdır.",
    thumbnail: "../assets/maxresdefault.jpg",
  },
]);
</script>

<template>
  <div class="mt-4 ml-72 z-50 w-[1780px]">
    <div class="flex flex-wrap">
      <div v-for="video in videos" :key="video.id" class="p-2 mb-8">
        <img
          class="thmb rounded-xl"
          src="../assets/maxresdefault.jpg"
          :alt="video.title"
        />
          <div class="flex items-start justify-start">
            <img
              id="img"
              draggable="false"
              class="rounded-full mt-2"
              alt=""
              width="36px"
              height="36px"
              src="https://yt3.ggpht.com/t1gVF0UZb3h6E7KH8ElfWBJuPa5DO0szjSYG1lEXZjRKKLW_g2n8AbEmhPVeZV_Nfwgc8AfISsU=s68-c-k-c0x00ffffff-no-rj"
            />
            <h3 class="text-white text-lg font-bold mt-2 ml-3">{{ video.title }}</h3>
          </div>
          <p class="dsc ml-12 text-sm -mt-1">{{ video.description }}</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.thmb {
  width: 305px;
  height: 180px;
}

.dsc {
  color: #ABABAA;
}
</style>
