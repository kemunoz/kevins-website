<template>
  <ul class="nav">
    <li class="nav-item fs-3">
      <a class="nav-link active" aria-current="page" @click="blah"> About </a>
    </li>
  </ul>
</template>
<script lang="ts">
import Vue from "vue";
export default class NavBar extends Vue {
  blah() {
    console.log("clicked");
  }
}
</script>
