<template>
  <div class="parks">
    <h1>Parks</h1>
    <Park />
  </div>
</template>

<script>
import Park from "../components/Park.vue";
export default {
  name: "Parks",
  components: {
    Park,
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
</style>