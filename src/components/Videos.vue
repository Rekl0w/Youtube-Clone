<script setup>
import Filters from "./Filters.vue";
import { ref } from "vue";

const videos = ref([
  {
    id: 1,
    title: "Unraveling Ancient Mysteries",
    description:
      "Join ArchaeoExplorer as we uncover the secrets of long-lost civilizations.",
    uploader: "ArchaeoExplorer",
    views: "1.7M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/1.jpg",
  },
  {
    id: 2,
    title: "Journey to the Stars",
    description:
      "Embark on a mesmerizing journey through the cosmos with StarGazer.",
    uploader: "StarGazer",
    views: "900K views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/2.jpg",
  },
  {
    id: 3,
    title: "Nature's Symphony",
    description:
      "Immerse yourself in the enchanting beauty of Earth's natural wonders with NatureSounds.",
    uploader: "NatureSounds",
    views: "2.5M views",
    postedAgo: "1 month ago",
    img: "/src/assets/3.jpg",
  },
  {
    id: 4,
    title: "Tech Talk: Future Innovations",
    description:
      "TechEnthusiast explores groundbreaking innovations that will shape our future.",
    uploader: "TechEnthusiast",
    views: "1.4M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/4.jpg",
  },
  {
    id: 5,
    title: "Global Gastronomy Adventure",
    description:
      "FoodExplorer takes you on a culinary journey to discover mouth-watering dishes worldwide.",
    uploader: "FoodExplorer",
    views: "1.9M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/5.jpg",
  },
  {
    id: 6,
    title: "Illusions: Beyond Imagination",
    description:
      "Prepare to be amazed by MindBlower's mind-bending illusions and magical performances.",
    uploader: "MindBlower",
    views: "2.8M views",
    postedAgo: "4 weeks ago",
    img: "/src/assets/6.jpg",
  },
  {
    id: 7,
    title: "Secrets of History",
    description:
      "HistoricalExplorer uncovers the hidden tales and mysteries of our past.",
    uploader: "HistoricalExplorer",
    views: "1.6M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/7.jpg",
  },
  {
    id: 8,
    title: "Extreme Sports Thrills",
    description:
      "AdrenalineRush brings you heart-pounding moments from the world of extreme sports.",
    uploader: "AdrenalineRush",
    views: "1.1M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/8.jpg",
  },
  {
    id: 9,
    title: "Wildlife Safari: Up Close",
    description:
      "WildlifeAdventurer gets you up close with majestic animals in their natural habitats.",
    uploader: "WildlifeAdventurer",
    views: "2.2M views",
    postedAgo: "1 month ago",
    img: "/src/assets/9.jpg",
  },
  {
    id: 10,
    title: "Space Oddities Unveiled",
    description:
      "ExploreSpace reveals the bizarre and unexplained phenomena lurking in the cosmos.",
    uploader: "ExploreSpace",
    views: "1.3M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/10.jpg",
  },
  {
    id: 11,
    title: "Artistic Marvels Showcase",
    description:
      "ArtistryUnleashed takes you on a visual journey through breathtaking artistic creations.",
    uploader: "ArtistryUnleashed",
    views: "2.0M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/11.jpg",
  },
  {
    id: 12,
    title: "Gaming Galaxy: Latest Trends",
    description:
      "GameMaster explores the latest trends and exciting developments in the gaming universe.",
    uploader: "GameMaster",
    views: "1.5M views",
    postedAgo: "4 weeks ago",
    img: "/src/assets/12.jpg",
  },
  {
    id: 13,
    title: "Mindful Living Guide",
    description:
      "WellnessExplorer shares practical tips and practices for achieving holistic well-being.",
    uploader: "WellnessExplorer",
    views: "2.4M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/13.jpg",
  },
  {
    id: 14,
    title: "Fashion Forward: Style Trends",
    description:
      "StyleMaven explores the latest trends and styles in the ever-evolving world of fashion.",
    uploader: "StyleMaven",
    views: "1.8M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/14.jpg",
  },
  {
    id: 15,
    title: "Musical Wonders Showcase",
    description:
      "MusicHarmony discovers extraordinary musical talents and mesmerizing performances.",
    uploader: "MusicHarmony",
    views: "2.6M views",
    postedAgo: "1 month ago",
    img: "/src/assets/15.jpg",
  },
  {
    id: 16,
    title: "DIY Delights: Creative Projects",
    description:
      "CreativeEnthusiast presents fun and creative do-it-yourself projects for every enthusiast.",
    uploader: "CreativeEnthusiast",
    views: "1.2M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/16.jpg",
  },
  {
    id: 17,
    title: "Literary Adventures: Book Reviews",
    description:
      "BookwormDelight explores thrilling page-turners and literary masterpieces from various genres.",
    uploader: "BookwormDelight",
    views: "1.7M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/17.jpg",
  },
  {
    id: 18,
    title: "Science Wonders: Experiments Unleashed",
    description:
      "ScienceEnigma conducts mind-blowing experiments that defy the laws of nature.",
    uploader: "ScienceEnigma",
    views: "2.1M views",
    postedAgo: "4 weeks ago",
    img: "/src/assets/18.jpg",
  },
  {
    id: 19,
    title: "Photography Showcase: Travel Edition",
    description:
      "TravelShutter captures the beauty of the world through the lens of talented photographers.",
    uploader: "TravelShutter",
    views: "1.4M views",
    postedAgo: "2 weeks ago",
    img: "/src/assets/19.jpg",
  },
  {
    id: 20,
    title: "Haunted Histories: Spooky Tales",
    description:
      "GhostHunterChronicles uncovers the spooky and mysterious tales from history's dark corners.",
    uploader: "GhostHunterChronicles",
    views: "2.3M views",
    postedAgo: "3 weeks ago",
    img: "/src/assets/20.jpg",
  },
]);

const truncateDescription = (description) => {
  if (description.length > 50) {
    return description.slice(0, 50) + "...";
  }
  return description;
};

</script>

<template>
  <Filters class="fixed z-30 mt-16" />
  <div class="mt-36 ml-72 z-50 w-[1780px] cursor-pointer">
    <div class="flex flex-wrap">
      <div v-for="video in videos" :key="video.id" class="p-2 mb-4">
        <img
          class="thmb rounded-xl"
          :src="video.img"
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
          <div>
            <h3
              :class="video.title.length >= 50 ? '' : ''"
              class="text-white text-m font-bold mt-2 ml-3 w-64"
            >
              <span class="tooltip" :title="video.title">{{
                truncateDescription(video.title)
              }}</span>
            </h3>
            <p class="dsc1 ml-3 text-sm cursor-pointer">
              <span class="tooltip1" :title="video.uploader">{{
                video.uploader
              }}</span>
            </p>
            <p class="dsc ml-3 text-sm cursor-pointer">
              {{ video.views }} • {{ video.postedAgo }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.thmb {
  width: 305px;
  height: 180px;
}

.dsc1 {
  color: #ababaa;
}

.dsc1:hover {
  color: #fff;
}

.dsc {
  color: #ababaa;
}

.tooltip1 {
  position: relative;
  cursor: pointer;
}

.tooltip1::after {
  content: attr(title);
  position: absolute;
  bottom: 150%;
  left: 0%;
  padding: 4px 8px;
  background-color: gray;
  border-radius: 4px;
  color: #fff;
  font-size: 12px;
  white-space: nowrap;
  opacity: 1;
  visibility: hidden;
}

.tooltip1:hover::after {
  opacity: 0.9;
  visibility: visible;
}
</style>
