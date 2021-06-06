<template>
  <head>
    <meta charset="UTF-8">
    <!-- https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP -->
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self'">
    <meta http-equiv="X-Content-Security-Policy" content="default-src 'self'; script-src 'self'">
    <title>{{title}}</title>
  </head>
</template>
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "Menu",
    props: {
        title: String,
    },
});
</script>