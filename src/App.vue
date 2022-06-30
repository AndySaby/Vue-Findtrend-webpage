<template>
  <AppHero />
  <AppSectionOne />
  <AppSectionTwo />
  <AppSection3 />
  <AppSection4 />
  <AppFooter />
</template>

<script>
import AppHero from "@/components/AppHero.vue";
import AppSectionOne from "@/components/AppSection1.vue";
import AppSectionTwo from "@/components/AppSection2.vue";
import AppSection3 from "@/components/AppSection3.vue";
import AppSection4 from "@/components/AppSection4.vue";
import AppFooter from "@/components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHero,
    AppSectionTwo,
    AppSection3,
    AppSectionOne,
    AppSection4,
    AppFooter,
  },
  data() {
    return {};
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
