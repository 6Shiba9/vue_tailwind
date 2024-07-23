<template>
  <herder class="">
    <div class="flex justify-center p-8">
      <div class="font-bold text-xl">Recent</div>
      <div class="w-[1020px]"></div>
      <div herf="/see all" class="text-[#1f8cf1] block hover:underline">
        See all
      </div>
    </div>
  </herder>
  <div class="flex space-x-4 justify-center">
    <card class="bg-gradient-to-r from-[#51ABFF] to-[#BD00FF] c-d">
      <div class="flex"></div>
      <div class="flex justify-center w-full">
        <img src="../assets/img/ts.png" class="h-20 m-12" />
      </div>
      <div class="bg-text">
        <div class="h1">TypeScript 101</div>
        <div class="py-2 text-gray-700">
TypeScript is a programming language developed and maintained by Microsoft.
        </div>
        <div></div>
        <div class="btn">Read ></div>
      </div>
    </card>
    <div class="p-1"></div>
    <card class="bg-gradient-to-r from-[#BD00FF] to-[#FF8951] c-d">
      <div class="flex"></div>
      <div class="flex justify-center w-full">
        <img src="../assets/img/phoenix.png" class="h-20 m-12" />
      </div>
      <div class="bg-text">
        <div class="h1">Learn Phoenix</div>
        <div class="py-2 text-gray-700">
Phoenix is a web development framework written in the functional programming language Elixir. 
        </div>
        <div></div>
        <div class="btn">Read ></div>
      </div>
    </card>
    <div class="p-1"></div>
    <card class="bg-gradient-to-r from-[#00FFD1] to-[#FF3F3F] c-d">
      <div class="flex"></div>
      <div class="flex justify-center">
        <img src="../assets/img/rails.png " class="h-20 m-12" />
      </div>
      <div class="bg-text">
        <div class="h1">Learn Ruby on Rails</div>
        <div class="py-2 text-gray-700">
Ruby on Rails, or Rails, is a server-side web application framework written in Ruby.
        </div>
        <div class="btn">Read ></div>
      </div>
    </card>
  </div>
</template>
<script>
export default {};
</script>
<style>
.c-d {
  @apply flex flex-col w-[360px] h-[490px] rounded-[20px] justify-between filter drop-shadow-xl;
}
.h1 {
  @apply font-bold text-2xl;
}
.btn {
  @apply bg-[#ffffff] p-2 w-[70px] rounded-[10px] hover:bg-[#cacaca] filter drop-shadow-md text-black;
}
.bg-text {
  @apply bg-white p-6 rounded-b-[20px] h-[243px];
}
</style>
