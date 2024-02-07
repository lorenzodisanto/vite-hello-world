<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components: { AppTitle, AppHero },
};
</script>

<template>
  <div class="wrapper">
    <AppTitle />
    <AppHero />
  </div>
</template>

<style>
@import url("./assets/main.css");
</style>
