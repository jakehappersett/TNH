<template>
  <div>
    <img alt="Anime Face" src="../assets/Anime_Face.png" />
    <h1>We know why you're here</h1>
    <h2>And we're here to help you out</h2>
    Run using Node.js <span id="node-version"></span>, Chromium
    <span id="chrome-version"></span>, and Electron
    <span id="electron-version"></span>.
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Landing",
  components: {
  },
  data() {
    return {
      title: "TNH | We know why you're here",
    };
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
