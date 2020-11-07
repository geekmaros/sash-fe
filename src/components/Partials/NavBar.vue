<template>
  <nav class="flex justify-between items-center ">
    <div class="">
      <img src="../../assets/Logo.png" alt="Sash Logo" />
      <!--      <MobileLogo class="block md:hidden" />-->
      <!--      <LargerScreenLogo class="hidden md:block" />-->
    </div>
    <div class="left-nav flex items-center">
      <a href="https://twitter.com/getsash" target="_blank" class="mr-sash15">
        <TwitterLogo
          class="block transform transition-all duration-500 ease-in-out hover:rotate-360 md:hidden"
        />
        <TwitterLogoMd
          class="hidden transform transition-all duration-500 hover:rotate-360 ease-in-out md:block"
        />
      </a>
      <a href="https://twitter.com/getsash" target="_blank" class="mr-sash15">
        <TwitterLogo
          class="block transform transition-all duration-500 ease-in-out hover:rotate-360 md:hidden"
        />
        <TwitterLogoMd
          class="hidden transform transition-all duration-500 hover:rotate-360 ease-in-out md:block"
        />
      </a>
      <a href="https://twitter.com/getsash" target="_blank" class="mr-sash15">
        <TwitterLogo
          class="block transform transition-all duration-500 ease-in-out hover:rotate-360 md:hidden"
        />
        <TwitterLogoMd
          class="hidden transform transition-all duration-500 hover:rotate-360 ease-in-out md:block"
        />
      </a>
      <a href="https://twitter.com/getsash" target="_blank" class="mr-sash15 ">
        <TwitterLogo
          class="block transform transition-all duration-500 ease-in-out hover:rotate-360 md:hidden"
        />
        <TwitterLogoMd
          class="hidden transform transition-all duration-500 hover:rotate-360 ease-in-out md:block"
        />
      </a>
      <a href="https://twitter.com/getsash" target="_blank" class="mr-sash15 ">
        <TwitterLogo
          class="block transform transition-all duration-500 ease-in-out hover:rotate-360 md:hidden"
        />
        <TwitterLogoMd
          class="hidden transform transition-all duration-500 hover:rotate-360 ease-in-out md:block"
        />
      </a>
      <a href="">
        <button
          class="bg-sashgreen h-full text-white rounded-full text-sm leading-18 py-sash12 px-sash40 font-bold"
        >
          Get Sash
        </button>
      </a>
    </div>
  </nav>
</template>

<script>
// import MobileLogo from "@/components/UIElements/MobileLogo";
// import LargerScreenLogo from "@/components/UIElements/LargerScreenLogo";
import TwitterLogo from "@/components/UIElements/TwitterLogo";
import TwitterLogoMd from "@/components/UIElements/TwitterLogoMd";
export default {
  name: "NavBar",
  components: { TwitterLogo, TwitterLogoMd }
};
</script>

<style scoped></style>
