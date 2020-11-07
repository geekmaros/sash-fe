<template>
  <div
    class="home overflow-y-hidden bg-white font-serif pt-12s pb md:pt-sash23 md:pl-sash165 pr-10 md:pr-sash165"
  >
    <HeroSection class="" />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
//import NavBar from "../components/Partials/NavBar";
import HeroSection from "../components/UIElements/HeroSection";

export default {
  name: "Home",
  components: {
    HeroSection
  }
};
</script>
