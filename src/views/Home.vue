<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />-->
    <Profile />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import Profile from "@/components/Profile.vue";
@Component({
  components: {
    HelloWorld,
    Profile,
  },
})
export default class Home extends Vue {}
</script>
