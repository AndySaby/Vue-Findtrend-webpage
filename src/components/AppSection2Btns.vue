<template>
  <button>
    <img :src="brandsIcon" alt="" />
  </button>
</template>

<script>
export default {
  name: "AppSectionBtns",
  components: {},
  props: ["brandsIcon"],
  data() {
    return {};
  },
};
</script>

<style scoped>
button {
  width: 266px;
  height: 120px;
  background: #f5f5f5;
  border-radius: 8px;
  border: none;
  margin: 32px;
}
</style>
