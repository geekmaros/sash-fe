<template>
  <div
    class="home  overflow-y-hidden bg-white font-serif pt-12s pb md:pt-sash23 overflow-x-hidden"
  >
    <HeroSection class="" />
    <MainContent />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
//import NavBar from "../components/Partials/NavBar";
import HeroSection from "../components/UIElements/HeroSection";
import MainContent from "../components/MainContent";

export default {
  name: "Home",
  components: {
    MainContent,
    HeroSection
  }
};
</script>
