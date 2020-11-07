<template>
  <footer class="bg-sashblack pt-16 h-auto lg:px-sash9">
    <div class="svg flex justify-center items-center pb-sash13">
      <svg
        width="121"
        height="11"
        viewBox="0 0 121 11"
        fill="none"
        class="hidden md:block"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M115.5 0H5.5C2.46243 0 0 2.46243 0 5.5C0 8.53757 2.46243 11 5.5 11H115.5C118.538 11 121 8.53757 121 5.5C121 2.46243 118.538 0 115.5 0Z"
          fill="#30C684"
        />
      </svg>
      <svg
        class="block md:hidden"
        width="42"
        height="4"
        viewBox="0 0 42 4"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M40 0H2C0.89543 0 0 0.89543 0 2C0 3.10457 0.89543 4 2 4H40C41.1046 4 42 3.10457 42 2C42 0.89543 41.1046 0 40 0Z"
          fill="#30C684"
        />
      </svg>
    </div>
    <div
      class="main-heading font-black leading-51 text-center text-25 text-white px-5"
    >
      <h1>Scale Better</h1>
    </div>
    <div
      class="sub-text text-white font-normal leading-30 text-center text-sm md:text-base md:text-xl lg:text-2xl px-2 md:px-2  lg:px-27"
    >
      <P
        >Built by a passionate tightly-knit product team to help African
        merchants experience the future of commerce and to support their
        growth.</P
      >
    </div>
    <div
      class="form-group h-sash23 md:h-51 md:pl-20 md:pr-10 lg:pr-32 lg:pl-40 mt-10 md:mt-sash37"
    >
      <SubscribeForm class=" pl-4 ml-2 md:px-4" />
    </div>
    <p
      class="text-center text-sm md:text-base lg:text-xs text-white font-medium pt-12 pb-10"
    >
      All rights reserved <span class="text-sm"> &copy; 2020</span>
    </p>
  </footer>
</template>

<script>
import SubscribeForm from "@/components/UIElements/SubscribeForm";
export default {
  name: "Footer",
  components: { SubscribeForm }
};
</script>

<style scoped lang="scss">
footer {
  @media screen and (min-width: 1024px) {
    .sub-text {
      padding: 0 10rem;
    }
    .form-group {
      padding-left: 13rem;
      padding-right: 10rem;
    }
  }
}
</style>
