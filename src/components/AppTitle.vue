<script>
export default {
  data() {
    return {
      title: "La mia prima app con vite",
    };
  },
};
</script>
<template>
  <h1>
    <h1 class="red">{{ title }}</h1>
  </h1>
</template>
<style scoped>
.red {
  color: red;
}
</style>
