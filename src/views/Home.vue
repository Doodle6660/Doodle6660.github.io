<template>
  <div
    class="h-screen flex flex-col bg-gradient-to-b from-primary to-secondary"
  >
    <app-header />
    <HelloWorld />
  </div>
  <app-content />
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import Content from "@/components/Content.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    "app-header": Header,
    "app-content": Content
  }
};
</script>
