<script setup>
import { ref } from 'vue';

const filterButtons = ref([
'Music', 'Games', 'Mix', 'Live', 
  'Action-adventure games', 'Sports Video Games', 'Football', 'Cooking',
  'Last Uploads', 'Watched', 'New Suggestions'
]);

</script>

<template>
  <div class="bg-black overflow-hidden flex items-end w-full justify-start h-16 ">
    <div class="ml-72 flex">
        <div class="flex justify-center items-center bg-white text-black font-semibold rounded-xl min-w-fit p-4 h-8 ml-4 mb-3 cursor-pointer">
            <button>
                <p>All</p>
            </button>
        </div>
        <div v-for="button in filterButtons" :key="button" class="filter-btn flex justify-center items-center text-white font-semibold rounded-xl min-w-fit p-4 h-8 ml-4 mb-3 cursor-pointer">
            <button>
                <p>{{ button }}</p>
            </button>
        </div>
    </div>
  </div>
</template>

<style scoped>
.filter-btn {
    background-color: #272727;
}

.filter-btn:hover {
    background-color: #3F3E3E;
}
</style>
