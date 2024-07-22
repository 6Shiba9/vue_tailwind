<script setup>
import alert_bar from "./components/alert_bar.vue";
import navbar from "./components/navbar.vue";
import crad from "./components/crad.vue";
import slider from "./components/slider.vue";
import contactbox from "./components/contactbox.vue";
import recent from "./components/recent.vue";
import categories from "./components/categories.vue";
import boxfooter from "./components/boxfooter.vue";
</script>
<template>
  <div class="kanit-regular">
    <header>
      <div>
        <alert_bar />
      </div>
      <div>
        <navbar />
      </div>
    </header>
    <div>
     <slider />
    </div>
    <div>
      <crad />
    </div>
    <div>
      <contactbox />
    </div>
    <div>
      <recent />
    </div>
    <div>
      <categories />
    </div>
    <footer>
      <boxfooter />
    </footer>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

.kanit-regular {
  font-family: "Kanit", sans-serif;
  font-weight: 400;
  font-style: normal;
}
</style>
