<template>
  <div id="sectionContainer">
    <p id="sectionHeader">All platform connect to Findtrend</p>

    <div id="imageWrapper">
      <img src="@/assets/platform.png" alt="" />
      <img id="tweet1" src="@/assets/tweet1.png" alt="" />
      <img id="tweet2" src="@/assets/tweet2.png" alt="" />
      <img id="tweet3" src="@/assets/tweet3.png" alt="" />
    </div>

    <button>View More Trend</button>
  </div>
</template>

<script>
import btns from "@/components/AppSection2Btns.vue";
export default {
  name: "AppSection3",
  components: { btns },
  data() {
    return {};
  },
};
</script>

<style scoped>
#sectionContainer {
  background: #fafafa;
  width: 100%;
}

#sectionHeader {
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  text-align: center;
  color: #000000;
  padding: 140px 0 80px 0;
}
#imageWrapper {
  margin-left: 140px;
}
#tweet1 {
  margin: 78px 0 44px 180px;
}
#tweet2 {
  margin: 0 0 40px 180px;
}
#tweet3 {
  margin: 0 0 80px 180px;
}
button {
  width: 198px;
  height: 57px;
  background: #000000;
  border-radius: 40px;
  border: none;
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 140%;
  text-align: center;
  color: #ffffff;
  margin: 0 0 140px 600px;
}
</style>
