<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
    <UiInput/>
    <UiButton/>
    <ui-button type="0"/>
    <ui-button msg="Welcome to Your Vue.js + 1" type="1" />
    <ui-button msg="Welcome to Your Vue.js + 2" type="2" />
  </div>
</template>

<!-- <script  lang="ts"> -->
<script>
import { Options, Vue } from "vue-class-component";
// import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import { UiButton, UiInput } from "share_ui";

@Options({
  components: {
    // HelloWorld,
    UiButton,
    UiInput
  },
})
export default class Home extends Vue {}
</script>
