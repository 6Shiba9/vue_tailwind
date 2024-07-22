<template>
  <div class="flex justify-center items-center">
    <swiper
      :slides-per-view="1"
      :space-between="50"
      @swiper="onSwiper"
      @slideChange="onSlideChange"
    >
      <swiper-slide v-for="slide in slides" :key="slide.id" class="p-6">
        <div class="slider_card">
          <div class="flex flex-col gap-3 justify-center p-10">
            <div class="text-6xl font-bold">{{ slide.title }}</div>
            <div class="w-[500px] text-3xl text-gray-500">
              {{ slide.content }}
            </div>
            <div>
              <a :href="slide.link" target="_blank" class="btn_s">Read ></a>
            </div>
            <div></div>
          </div>
          <div class="flex justify-center items-center m-auto w-full relative">
            <img :src="slide.image" class="h-[282px] z-50" />
            <img
              :src="slide.image"
              class="h-[552px] absolute opacity-30 blur-[70px] z-40"
            />
          </div>
        </div>
      </swiper-slide>

    </swiper>
  </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";
import figmaLogo from "../assets/img/figma.png";
import vuelogo from "../assets/img/vue.png";
import Nodelogo from "../assets/img/node.png";

const slides = [
  {
    id: 1,
    title: "Figma Course",
    content:
      "Figma is a vector graphics editor and prototyping tool which is primarily web-based.",
    image: figmaLogo,
    link: "https://www.figma.com/community",
  },
  {
    id: 2,
    title: "Vue Framework",
    content:
      "An approachable, performant and versatile framework for building web user interfaces.",
    image: vuelogo,
    link: "https://vuejs.org/",
  },
  {
    id: 3,
    title: "NodeJS",
    content:
      "Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.",
    image: Nodelogo,
    link: "https://nodejs.org/en/",
  },
];

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log("slide change");
    };
    return {
      onSwiper,
      onSlideChange,
      slides,
    };
  },
};
</script>

<style>
.slider_card {
  @apply flex flex-row justify-between w-[1200px] h-[600px] bg-white shadow-xl rounded-lg mx-auto;
}
.btn_s {
  @apply bg-[#F5F5F5] p-2 w-[70px] rounded-[10px] hover:bg-[#cacaca] filter drop-shadow-md text-black;
}

</style>
