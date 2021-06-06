<template>
  <div class="container">
    <Menu />
    <Landing />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Landing from "./views/Landing.vue";
import Menu from "./components/Menu.vue";

export default defineComponent({
  name: "App",
  components: {
    Landing,
    Menu,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
