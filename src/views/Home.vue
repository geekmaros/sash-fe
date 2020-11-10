<template>
  <div
    class="home  overflow-y-hiddens bg-white font-serif pt-12s pb md:pt-sash23 overflow-x-hidden"
  >
    <div
      class="header-image absolute right-0 top-0 mt-lgherotop hidden z-50 md:mr-7"
    >
      <img
        src="../assets/images/Header-image.png"
        alt="Header Image"
        class="z-50"
      />
    </div>
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
