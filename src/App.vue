<template>
  <div id="app">
    <router-view />
  </div>
</template>

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
