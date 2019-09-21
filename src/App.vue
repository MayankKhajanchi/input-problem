<template>
  <div id="app">
    <div class="container pt-5">
      <HelloWorld :dataset="dataset"/>
      <HelloWorld :dataset="dataset"/>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Vue from "vue";
export default {
  name: "app",
  components: {
    HelloWorld
  },
  data() {
    return {
      dataset: ["A", "B", "C", "D"]
    };
  }
};
</script>
