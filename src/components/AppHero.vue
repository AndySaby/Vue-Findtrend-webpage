<template>
  <div id="background">
    <Navbar />

    <div id="hero-text">
      <p class="headerText">Minimize your tabs.</p>
      <p class="headerText" id="header2">Find the trends!</p>
      <p class="subtext">
        Don’t let your computer memories consumes all of those browser tabs.
      </p>
      <p class="subtext">
        Findtrend let you gathers all of your favorite website into one place.
      </p>

      <div id="btn-cont">
        <button><img src="@/assets/getstarted.png" alt="" /></button>
        <img src="@/assets/img-hero.png" alt="" id="icon" />
      </div>
      <div id="framesContainer">
        <frame
          v-for="social in Socials"
          :key="social.id"
          :image="social.url"
          :text="social.text"
          :close="social.logo"
        />
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/AppNav.vue";
import frame from "@/components/HeroCards.vue";

export default {
  name: "AppHero",
  components: { Navbar, frame },
  data() {
    return {
      Socials: [
        {
          id: "card1",
          url: require("@/assets/twitter.png"),
          text: "Cryptopunk - Search",
          logo: require("@/assets/closeIcon.png"),
        },

        {
          id: "card2",
          image: require("@/assets/pinterest.png"),
          text: "Popular Design - Search",
          logo: require("@/assets/closeIcon.png"),
        },

        {
          id: "card3",
          image: require("@/assets/basketball.svg"),
          text: "Popular Design - Search",
          logo: require("@/assets/closeIcon.png"),
        },

        {
          id: "card4",
          image: require("@/assets/ballicon.png"),
          text: "Elon Musk - Search",
          logo: require("@/assets/closeIcon.png"),
        },
      ],
    };
  },
};
</script>

<style scoped>
#background {
  background: #000000;
  width: 100%;
  height: fit-content;
  z-index: -1;
}
.headerText {
  font-family: "Effra";
  font-style: normal;
  font-weight: 900;
  font-size: 72px;
  line-height: 112%;
  text-align: center;
  color: #ffffff;
}
#header2 {
  margin-bottom: 24px;
}
.subtext {
  font-family: "Effra";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  text-align: center;
  color: #8b8b8b;
}
button {
  width: 180px;
  height: 57px;
  background: #a8ff35;
  border-radius: 40px;
  margin: 40px 0 110px 0;
}
#btn-cont {
  margin: 0 0 0 630px;
}
#icon {
  margin-top: 28px;
}
#framesContainer {
  display: flex;
  padding-bottom: 108px;
}
</style>
