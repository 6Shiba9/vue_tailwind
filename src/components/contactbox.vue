<template>
  <div class="flex justify-center py-10">
    <div class="flex boxstyle justify-between">
        <div></div>
      <div class="flex justify-center items-center">
        <div class="flex w-[100px] h-[100px] bg-white items-center justify-center rounded-xl">
        <img src="../assets/img/email.png" class="h-10" />
        </div>
      </div>
      <div class="flex justify-center flex-col">
        <div class="font-bold flex">The best Newsletter on the web</div>
        <div class="text-gray-700">
          Recieve posts updates straight to your inbox, 
        </div>
        <div class="text-gray-700">including fulladditional posts.</div>
      </div>
      <div class="flex justify-center items-center">
        <div class="flex pr-4">
        <input type="text" placeholder="Email Address" class="w-[300px] h-[40px] rounded-lg pl-4"/>
        </div>
        <div class="btn_style">Subscribe ></div>
      </div>
      <div></div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.boxstyle {
  @apply bg-gray-200 w-[1200px] h-[180px] rounded-[20px];
}
.btn_style {
  @apply bg-white flex w-[128px] h-[42px] font-bold rounded-lg justify-center items-center hover:bg-gray-300;
}
</style>
