<template>
  <div class="row">
      <img alt="Anime Face" class="img-fluid main-image mx-auto" src="../assets/Anime_Face.png" />
  </div>
  <div class="row">
    <div class="col">
      <h1>We know why you're here</h1>
    </div>
  </div>
  <div class="row">
    <div class="col">
      <h3>And we're here to help you out</h3>
    </div>
  </div>
  <div class="row">
    <div class="col">
      Run using Node.js <span id="node-version"></span>, Chromium
      <span id="chrome-version"></span>, and Electron
      <span id="electron-version"></span>.
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Landing",
  components: {},
});
</script>
<style scoped>
.main-image {
  max-height: 500px;
}
</style>
