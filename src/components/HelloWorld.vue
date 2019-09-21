<template>
  <div class="hello">
    <div class="row">
      <div class="col-3 mb-2" v-for="(item, index) in dataset" :key="index">
        {{index + 1}}<input class="ml-2" type="text" v-model="dataset[index]"/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  },
  props: ["dataset"]
};
</script>
