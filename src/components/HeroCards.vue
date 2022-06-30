<template>
  <div id="frame">
    <img :src="image" alt="" />
    <p id="f-description">{{ text }}</p>
    <img :src="close" alt="" />
  </div>
</template>

<script>
export default {
  name: "HeroCards",
  props: ["image", "text", "close"],
  components: {},
  data() {
    return {};
  },
};
</script>

<style scoped>
#frame {
  width: 341.23px;
  height: 82px;
  background: #181818;
  transform: rotate(-4deg);
}
#f-description {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 23.8065px;
  line-height: 28px;
  text-align: center;
  color: #ffffff;
  transform: rotate(-4deg);
  flex: none;
  order: 1;
  flex-grow: 0;
}
</style>
