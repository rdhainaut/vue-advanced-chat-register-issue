<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <VueChat />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import VueChat from "@/components/VueChat.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
    VueChat,
  },
})
export default class HomeView extends Vue {}
</script>
