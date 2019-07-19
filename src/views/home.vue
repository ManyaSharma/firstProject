<template>
  <div class="Home">
    <div class="background">
    <headerSection/>
		<navigationSection/>
		<card1/>
  </div>
  </div>
</template>

<script>
import headerSection from "@/components/headerSection.vue";
import navigationSection from "@/components/navigationSection.vue";
import card1 from "@/components/card1.vue";

export default {
  name: "home",
  components: {
    headerSection,
    navigationSection,
    card1
  }
};
</script>
<style lang="scss">
.background {
  background-image: url("../assets/lobby-bg.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 100vh;
}
</style>
