<template>
  <div class="home">
    <!--<img alt="Vue logo" src="../assets/logo.png" />-->
    <img
      src="https://nklayman.github.io/vue-cli-plugin-electron-builder/hero.png"
      alt="Vue logo"
      style="width: 70%"
    />
    <HelloWorld msg="Welcome to Your Vue.js + Electron App" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}
</script>
