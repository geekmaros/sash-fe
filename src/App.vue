<template>
  <div id="app" class="">
    <NavBar class="sticky top-0 bg-white z-50"></NavBar>

    <router-view />
    <Footer />
  </div>
</template>

<script>
import Footer from "./components/Partials/Footer";
import NavBar from "./components/Partials/NavBar";
export default {
  components: { NavBar, Footer }
};
</script>

<style lang="scss">
@import "assets/main";

@font-face {
  font-family: "Circular Std";
  src: url("assets/fonts/circular/CircularStd-Black.otf") format("opentype");
  font-style: normal;
  font-weight: 900;
}
@font-face {
  font-family: "Circular Std";
  src: url("assets/fonts/circular/CircularStd-Bold.otf") format("opentype");
  font-weight: 800;
  font-style: normal;
}

@font-face {
  font-family: "Circular Std";
  src: url("assets/fonts/circular/CircularStd-Book.otf") format("opentype");
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: "Circular Std";
  src: url("assets/fonts/circular/CircularStd-Medium.otf") format("opentype");
  font-weight: 500;
  font-style: normal;
}
#app {
  font-family: "Circular Std", serif;
}
</style>
