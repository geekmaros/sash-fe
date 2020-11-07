<template>
  <main class="">
    <div
      class="absolute z-40 inset-0 darker opacity-75s transition transition-all duration-500 ease-in-out bg-black"
    ></div>
    <div
      @click="$emit('closeModal')"
      class="fixed overflow-y-auto modal-inner inset-0 z-50 flex transition transition-all duration-500 ease-in-out overflow-x-hidden"
    >
      <div
        class="lg:w-3/12 md:w-6/12 my-40 md:my-17  md:my-32s mx-auto lg:my-auto flex flex-col justify-center items-center bg-white rounded-lg md:pb-12 pt-12 pb-10 md:pt-16 px-8  transition-all"
      >
        <div class="w-auto">
          <img class="" src="../../assets/svg/8.svg" alt="" />
        </div>

        <h1
          class=" text-lg font-black md:text-2xl lg:text-2xl text-center font-medium text-sashblack mt-5"
        >
          Awesome
        </h1>
        <h1
          class=" text-lg md:text-2xl lg:text-lg text-center text-sashblack mb-5"
        >
          You are on our waiting list
        </h1>
        <div @click="$emit('closeModal')" class="w-full cursor-pointer ">
          <div
            class="button w-full flex rounded-full justify-center items-center bg-sashgreen text-lg md:text-2xl lg:text-lg text-white px-4 py-3"
          >
            Done
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Modal",
  data() {
    return {};
  }
};
</script>

<style scoped lang="scss">
main {
  .darker {
    opacity: 0.8;
    z-index: 60;
  }
  .modal-inner {
    z-index: 70;
  }
}
</style>
