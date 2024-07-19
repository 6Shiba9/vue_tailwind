<template>
  <herder>
    <div class="flex  justify-around p-8">
      <div class="font-bold text-xl">Top</div>
      <div class="w-[220px]"></div>
      <div herf="/see all" class="text-[#1f8cf1] block hover:underline">
        See all
      </div>
    </div>
  </herder>
  <div class="flex space-x-4 justify-center">
    <card class="bg-gradient-to-r from-[#51ABFF] to-[#BD00FF] rounded-[20px] filter drop-shadow-xl c-dr">
      <div class="flex"></div>
      <div class="flex justify-center w-full">
        <img src="../assets/img/next_js.png" class="h-20 m-20" />
      </div>
      <div class="bg-text1">
        <div class="h1">Next.js Introduction</div>
        <div class="py-2 text-gray-700">
          Next.js is an open-source development framework built on top of
          Node.js.
        </div>
        <div></div>
        <div class="btn_c">Read ></div>
      </div>
    </card>
    <div class="p-7"></div>
    <card class="bg-gradient-to-r from-[#BD00FF] to-[#FF8951] rounded-[20px] filter drop-shadow-xl c-dr">
      <div class="flex"></div>
      <div class="flex justify-center">
        <img src="../assets/img/remix.png " class="h-20 m-20" />
      </div>
      <div class="bg-text1">
        <div class="h1">Remix Introduction</div>
        <div class="py-2 text-gray-700">
          Remix is a new framework that blurs the line between server and
          client.
        </div>
        <div class="btn_c">Read ></div>
      </div>
    </card>
  </div>
</template>
<script>
export default {};
</script>
<style>
.c-de {
  @apply flex flex-col w-[560px] h-[555px] justify-between;
}
.h1 {
  @apply font-bold text-2xl;
}
.btn_c {
  @apply bg-[#3DA2FF] p-2 w-[70px] rounded-[10px] text-white hover:bg-[#6491bb] filter drop-shadow-md;
}
.bg-text1 {
  @apply bg-white p-6 rounded-b-[20px] h-[230px];
}
</style>
