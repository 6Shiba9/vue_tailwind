<template >
      <herder >
    <div class="flex  justify-around p-8">
      <div class="font-bold text-xl">Categories</div>
      <div class="w-[220px]"></div>
      <div herf="/see all" class="text-[#1f8cf1] block hover:underline">
        See all
      </div>
    </div>
  </herder>
    <div class="flex space-x-10 justify-center">
        <div class="card_c bg-gradient-to-r from-[#BD00FF] to-[#FF8951]">
            Code
        </div>
        <div class="card_c bg-gradient-to-r from-[#BD00FF] to-[#51ABFF]">
            Design
        </div>
        <div class="card_c bg-gradient-to-r from-[#FF3F3F] to-[#FF8951] ">
            Prototyping
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style >
    .card_c{
        @apply  w-[360px] h-[180px] flex justify-center items-center rounded-[20px]
        font-bold text-2xl text-white hover:underline;
    }
</style>