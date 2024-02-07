<script>
export default {
  data() {
    return {
      logo: "vue.logo.png",
    };
  },

  methods: {
    buildImagePath(imgName) {
      const imgUrl = new URL("../assets/img/" + imgName, import.meta.url);
      return imgUrl.href;
    },
  },
};
</script>
<template>
  <div class="jumbo">
    <h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</h2>
    <hr />
    <h3>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda in
      molestias sit
    </h3>
    <h4>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda in
      molestias sit
    </h4>
    <img :src="buildImagePath(logo)" class="logo" alt="" />
    <button class="btn">Lorem click</button>
  </div>
</template>
<style scoped>
.btn {
  display: block;
  padding: 5px;
  background-color: rgb(57, 143, 229);
  color: white;
  border-radius: 10px;
  cursor: pointer;
}

.logo {
  width: 200px;
}
</style>
