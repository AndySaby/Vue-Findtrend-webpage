<template>
  <div id="container">
    <p id="sectionHeader">Open new tabs is sh*t</p>
    <div id="boxWrapper">
      <img src="@/assets/iconRight.png" alt="" />

      <div id="midBox">
        <div id="centerbox">
          <img id="centerbox-img" src="@/assets/vector3.png" alt="" />
          <span id="box-text">Findtrend - Elon Musk</span>
          <img id="centerbox-close" src="@/assets/closeIcon.png" alt="" />
        </div>
      </div>

      <img src="@/assets/iconLeft.png" alt="" />
    </div>
    <p id="subText">
      A solution for your browser tabs and don’t make your device get slower over time.
      Get ease and faster to discover a trend with just one tab.
    </p>
  </div>
</template>

<script>
export default {
  name: "AppSection1",
  data() {
    return {};
  },
};
</script>

<style scoped>
#container {
  width: 100%;
  background: #a8ff35;
  height: fit-content;
}
#sectionHeader {
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 72px;
  line-height: 86px;
  text-align: center;
  color: #000000;
  padding: 140px 0 40px 0;
}
#boxWrapper {
  display: flex;
  align-items: center;
  padding: 0 0 60px 350px;
}

#midBox {
  width: 502px;
  background: #f5f5f5;
  border-radius: 16px;
  height: 202px;
  margin: 0 24px 0 26px;
  padding: 60px 80px;
}
img {
  width: 95px;
  height: 70px;
}
#subText {
  font-family: "Effra";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  text-align: center;
  color: #000000;
  width: 666px;
  height: 54px;
  margin: 0 auto;
  padding-bottom: 140px;
}
#centerbox {
  width: 341.23px;
  height: 82px;
  background: #030303;
}
#centerbox-img {
  width: 30px;
  height: 30px;
}
#centerbox-close {
  width: 15px;
  height: 15px;
}
#box-text {
  font-style: normal;
  font-weight: 400;
  font-size: 23.8064px;
  line-height: 28px;
  text-align: center;
  color: #ffffff;
  flex: none;
  order: 1;
  flex-grow: 0;
}
</style>
