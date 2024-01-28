<script >
export default {
  name: "App",
  data() {
    return {
      message: "Hello Vue!",
      text: "color-text",
      imageURL: "https://www.positivethinking.tech/wp-content/uploads/2021/01/Logo-Vuejs.png",
      image: "image-size"
    }
  },
}
</script>

<template>
  <header>
    <h1 :class="text"> {{ message }}</h1>
  </header>
  <main>
    <img :class="image" :src="imageURL" alt="Vue.js">
  </main>
</template>

<style ></style>
