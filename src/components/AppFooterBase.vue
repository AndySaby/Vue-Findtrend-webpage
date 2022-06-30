<template>
  <div id="greenbase">
    <p id="text">Join us on email for</p>
    <p id="subtext">more trending topics</p>
    <button>Join Now</button>
  </div>
</template>
<script>
export default {
  name: "AppFooter",
  components: [],
  data() {
    return {};
  },
};
</script>

<style scoped>
#greenbase {
  width: 100%;
  background: #a8ff35;
}
#text {
  font-style: normal;
  font-weight: 900;
  font-size: 72px;
  line-height: 112%;
  text-align: center;
  color: #000000;
  padding-top: 140px;
}
#subtext {
  font-style: normal;
  font-weight: 900;
  font-size: 72px;
  line-height: 112%;
  text-align: center;
  color: #87d322;
  padding-bottom: 40px;
}
button {
  width: 180px;
  height: 57px;
  background: #000000;
  border-radius: 40px;
  color: white;
  margin: 0 0 140px 630px;
}
</style>
