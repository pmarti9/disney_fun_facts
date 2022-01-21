<template>
  <div>
    <ul>
      <li>Magic Kingdom</li>
      <li>Epcot</li>
      <li>Hollywood Studios</li>
      <li>Animal Kingdom</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Park",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
ul {
  list-style-type: none;
  display: flex;
}
li {
  flex: auto;
}
</style>