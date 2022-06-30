<template>
  <div id="container">
    <p id="headerText">
      Findtrend helps you to increase your productivity and reduce your computer's memory
      load,
      <span id="headertext2"
        >an application that can fulfill your daily browsing needs.</span
      >
    </p>
    <p id="subtext">Findtrend make +1000 Startup grow</p>
  </div>
  <div id="btn-wrapper">
    <Buttons v-for="btn in btns" :key="btn.id" :brandsIcon="btn.icon" />
  </div>
</template>

<script>
import Buttons from "@/components/AppSection2Btns.vue";
export default {
  name: "AppSection2",
  components: { Buttons },
  data() {
    return {
      btns: [
        {
          id: "one",
          icon: require("@/assets/1.png"),
        },
        {
          id: "two",
          icon: require("@/assets/2.png"),
        },
        {
          id: "three",
          icon: require("@/assets/3.png"),
        },
        {
          id: "four",
          icon: require("@/assets/4.png"),
        },
        {
          id: "five",
          icon: require("@/assets/5.png"),
        },
        {
          id: "six",
          icon: require("@/assets/6.png"),
        },
        {
          id: "seven",
          icon: require("@/assets/7.png"),
        },
        {
          id: "eight",
          icon: require("@/assets/8.png"),
        },
        {
          id: "nine",
          icon: require("@/assets/9.png"),
        },
        {
          id: "ten",
          icon: require("@/assets/10.png"),
        },
        {
          id: "eleven",
          icon: require("@/assets/11.png"),
        },
        {
          id: "twelve",
          icon: require("@/assets/12.png"),
        },
        {
          id: "thirdteen",
          icon: require("@/assets/13.png"),
        },
        {
          id: "fourthteen",
          icon: require("@/assets/14.png"),
        },
        {
          id: "fifthteen",
          icon: require("@/assets/15.png"),
        },
        {
          id: "sixthteen",
          icon: require("@/assets/16.png"),
        },
      ],
    };
  },
};
</script>

<style scoped>
#container {
  background: #ffffff;
  width: 100%;
  height: fit-content;
}
#headerText {
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  color: #000000;
  padding: 140px;
}
#headertext2 {
  color: #adadad;
}
#subtext {
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  text-align: center;
  color: #000000;
  padding: 140px 0 80px 0;
}
#btn-wrapper {
  display: flex;
  flex-wrap: wrap;
  margin-left: 140px;
}
</style>
