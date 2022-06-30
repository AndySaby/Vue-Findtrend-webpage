<template>
  <div id="sectionContainer">
    <p id="sectionHeader">Get your best deal</p>
    <div id="seasonSection">
      <span id="monthly">Monthly</span>
      <button id="btn"><img src="@/assets/Toggle.png" alt="" /></button>
      <span id="yearly">Yearly</span>
      <img src="@/assets/yearicon.png" alt="" />
    </div>
  </div>

  <div></div>
</template>

<script>
import PaymentPlan from "@/components/AppSection4Cards.vue";
export default {
  name: "AppSection4",
  components: { PaymentPlan },
  data() {
    return {
      payment: [{ id: "card1" }, { id: "card2" }, { id: card3 }],
    };
  },
};
</script>

<style scoped>
#sectionContainer {
  width: 100%;
  background-color: black;
}
#sectionHeader {
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  text-align: center;
  color: #ffffff;
  padding: 140px 0 40px 0;
}
#seasonSection {
  display: flex;
  align-items: center;
  padding: 0 0 52px 560px;
}
#monthly {
  font-family: "Inter";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  color: #ffffff;
}
#yearly {
  font-family: "Inter";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  color: #f5f5f5;
  opacity: 0.5;
}
#btn {
  width: 104px;
  height: 52px;
  background: #ffffff;
  border-radius: 99px;
  border-radius: none;
  text-align: left;
  padding: 5px 8px;
  margin: 0 24px;
}
#circlebtn {
  width: 36px;
  height: 36px;
  background: #a8ff35;
  border-radius: 99px;
  border: none;
}
</style>
