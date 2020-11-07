<template>
  <header class="h-screen bg-blue-300">
    <NavBar class=""> </NavBar>
    <section
      class=" relative  h-screen   font-serif fle grid md:grid-cols-12  items-center"
    >
      <div
        class="heading lg:col-span-8 lg:text-justify text-center md:col-span-12 lg:mt-12s "
      >
        <div
          class="main-text text-sashblack text-mobiletext md:text-35 lg:text-48px lg:leading-112  ip:text-6xls font-black leading-tight"
        >
          <h1>A modern social</h1>
          <h2><span>commerce</span> app.</h2>
        </div>
        <div
          class="sub-text lg:max-w-2xl  text-15 md:leading-30  text-sashgray md:text-summobile lg:text-summobile mt-3 lg:mt-sash12 md:mt-sash133"
        >
          <p>
            Sash is a new way for customers to direct message,
          </p>
          <p>order from and pay merchants in a fun,</p>
          <p>fast and seamless way.</p>
        </div>

        <div class="download-options flex items-center md:mt-8">
          <a href="#">
            <img class="mr-4" src="../../assets/svg/ios.svg" alt=""
          /></a>
          <a
            href="#"
            class="transform hover:scale-125 transition-all duration-100"
          >
            <img src="../../assets/svg/googleplay.svg" alt=""
          /></a>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
import NavBar from "../Partials/NavBar";
export default {
  name: "HeroSection",
  data() {
    return {};
  },
  components: { NavBar }
};
</script>

<style scoped lang="scss">
section {
  span {
    cursor: pointer;
    position: relative;
    display: inline-block;
    -webkit-background-clip: text;
    color: #303037;
    background-repeat: no-repeat;
    transition: background 0.2s ease-out;
    white-space: nowrap;
  }

  h2 {
    position: relative;
  }

  h2:before {
    content: "";
    position: absolute;

    left: 0;
    right: 0;

    background: #30c684;
    bottom: 5px;
    transition: all 0.2s ease-out;
    @media screen and (max-width: 767px) {
      width: 9rem;
      margin: -2px auto;
      height: 7px;
    }

    @media screen and (min-width: 768px) {
      width: 16rem;
      margin: 3px auto;
      height: 10px;
    }

    @media screen and (min-width: 1026px) {
      width: 22rem;
      margin: 3px auto;
      height: 10px;
    }

    @media screen and (min-width: 1027px) {
      width: 15rem;
      height: 10px;
      margin-left: 0;
    }
  }

  //span:hover {
  //  background-position: 0 11px;
  //}
  //
  //h2:hover:before {
  //  transform: translateY(10px);
  //}
  //@media screen and (max-width: 1024px) {
  //  .form-group {
  //    padding-left: 17rem !important;
  //    padding-right: 17rem !important;
  //  }
  //}
  @media screen and (width: 1024px) {
    .form-group {
      padding-left: 17rem !important;
      padding-right: 17rem !important;
    }
  }
}
</style>
