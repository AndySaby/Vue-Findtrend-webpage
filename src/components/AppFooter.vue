<template>
  <greenbase />
  <div id="base">
    <div id="logowrap">
      <img id="icon" src="@/assets/Vector1.png" alt="" />
      <p id="iconName">Findtrend</p>
    </div>
    <div id="tabwrap">
      <li v-for="tab in tabs" :tab="tab">{{ tab }}</li>
    </div>
  </div>
</template>

<script>
import greenbase from "@/components/AppFooterBase.vue";

export default {
  name: "AppFooter",
  components: { greenbase },
  data() {
    return {
      tabs: ["Privacy Policy", "Terms and Conditions", "Contact Us", "Careers"],
    };
  },
};
</script>

<style>
#base {
  width: 100%;
  background: #ffffff;
  height: 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 100px 0 80px;
  flex-wrap: wrap;
}
#logowrap {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}
#icon {
  width: 40px;
  height: 40px;
  margin-right: 10px;
}
#tabwrap {
  display: flex;
  flex-wrap: wrap;
}
li {
  font-family: "Effra";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 100%;
  text-align: center;
  color: #000000;
  list-style: none;
  margin-left: 40px;
}
#iconName {
  font-family: "Inter";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 100%;
  text-align: center;
  color: #000000;
}
</style>
