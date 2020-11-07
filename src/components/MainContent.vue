<template>
  <main
    class="relative h-auto w-full bg-sashlightblues -mt-6 mt-56s lg:-mt-8 md:-mt-24"
  >
    <div class="bender hidden">
      <img src="../assets/svg/bendmd.svg" alt="Bender" />
    </div>
    <div class="absolute hero hidden px-5 -mt-13">
      <img
        width="900"
        src="../assets/svg/desktopheromobile.svg"
        class="block md:hidden"
        alt="Hero SVG"
      />
    </div>
    <div class="flex relative absolute justify-center items-center">
      <DirtyParticle
        class="absolute lg:mt-32  lg:mr-20 lg:right-auto right-0 -mr-32 md:-mr-7 "
      />
      <!--      <img src="../assets/svg/particlemd.svg.svg" alt="" />-->
    </div>
    <div class="particle absolute relative -ml-20 -mt-10 md:-ml-12">
      <Particles class="absolute" />
    </div>
    <div
      class="card-wrapper grids pb-12 md:pb-24 lg:pb-20  bg-sashlightblue  md:bg-transparent lg:bg-transparent lg:grid-cols-4 md:grid-cols-2 gap-4 top-0 mt-7 lg:mt-32 md:mt-24  lg:mr-8 md:pr-8 md:pl-10 lg:pl-20"
    >
      <header
        class="col header md:pr-0 md:pl-0 lg:mt-10 md:mt-32 mb-42 md:mb-sash28 lg:mb-0"
      >
        <div class="stroke flex justify-center items-center">
          <svg
            width="121"
            class="mb-sash17 hidden md:block"
            height="11"
            viewBox="0 0 121 11"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M115.5 0H5.5C2.46243 0 0 2.46243 0 5.5C0 8.53757 2.46243 11 5.5 11H115.5C118.538 11 121 8.53757 121 5.5C121 2.46243 118.538 0 115.5 0Z"
              fill="#30C684"
            />
          </svg>
          <svg
            class="block md:hidden mb-sash17"
            width="57"
            height="5"
            viewBox="0 0 57 5"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M54.4999 0H2.49988C1.11917 0 -0.00012207 1.11929 -0.00012207 2.5C-0.00012207 3.88071 1.11917 5 2.49988 5H54.4999C55.8806 5 56.9999 3.88071 56.9999 2.5C56.9999 1.11929 55.8806 0 54.4999 0Z"
              fill="#30C684"
            />
          </svg>
        </div>

        <div
          class="main-text text-center md:leading-51  text-sashblack text-lg md:text-sub  font-black leading-11"
        >
          <h1>Merchants struggle to convert prospects</h1>
          <h1>and manage their business on</h1>
          <h1>social media & messaging apps.</h1>
        </div>
        <div
          class="sub-text text-center leadin-30px text-sashgray text-15 md:text-xl  mt-sash12"
        >
          <p>
            Move your business conversations over to convert
          </p>
          <p>
            faster and improve productivity.
          </p>
        </div>
      </header>
      <div
        class="card mr-10 ml-10 md:ml-0 md:mr-0 transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer bg-white pt-49 shadow-lg rounded-lg text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Conversational</h1>
          <h1>Commerce:</h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          Do more within DM
        </h4>
        <div class="summary text-sashblack text-sm  mt-sash19 mb-sash25">
          <p>
            Delight your customers with a seamless
          </p>
          <p>messaging, ordering, check-out and</p>
          <p>payment experience.</p>
        </div>
        <div
          class="flex  justify-center items-center md:pl-sash71 md:pr-sash69 pl-sash435 pr-sash436 pb-sash492 mb-10"
        >
          <!--          <img src="../assets/svg/convercommmd.svg" alt="" />-->
          <img src="../assets/svg/1.svg" alt="" />
        </div>
      </div>
      <div
        class="card mr-10 ml-10 md:ml-0 md:mr-0 transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer md:-translate-y-12 shadow-lg  rounded-lg bg-white pt-49  text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Social</h1>
          <h1>Discovery:</h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          Grow Organically
        </h4>
        <div
          class="summary text-sashblack text-sm  mt-sash19 md:mb-sash495 mb-sash342"
        >
          <p>
            A new way for your customers and
          </p>
          <p>their friends to discover and promote your</p>
          <p>business & products.</p>
        </div>
        <div
          class="flex justify-center items-center mb-10 md:pl-sash49 md:pr-sash495 pl-sash305 pr-sash305 pb-sash349 "
        >
          <img src="../assets/svg/sd.svg" class="hidden md:block" alt="" />
          <img src="../assets/svg/sd.svg" class="hidden   md:hidden" alt="" />
          <img src="../assets/svg/sd.svg" class="block md:hidden" alt="" />
        </div>
      </div>
      <div
        class="card mr-10 ml-10 md:ml-0 md:mr-0 transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer shadow-lg  rounded-lg bg-white pt-49  text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Delivery Options</h1>
          <h1>& FAQs:</h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          Take care of trivial
        </h4>
        <div
          class="summary text-sashblack text-sm  mt-sash19 md:mb-sash245 mb-sash208"
        >
          <p>
            Set your delivery options, and provide
          </p>
          <p>ready-made answers to common questions</p>
          <p>to speed-up conversion.</p>
        </div>
        <div
          class="flex justify-center items-center md:mb-sash79 mb-10 md:pl-sash341 md:pr-sash347 pl-sash208 pr-sash221 pb-sash404"
        >
          <!--          <img src="../assets/svg/deliverymd.svg" alt="" />-->
          <img src="../assets/svg/3.svg" alt="" />
        </div>
      </div>
      <div
        class="cards mr-10 ml-10 md:ml-0 md:mr-0 transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer md:-translate-y-12 shadow-lg  rounded-lg bg-white pt-49  text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Product</h1>
          <h1>Catalogue:</h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          Showcase your hustle
        </h4>
        <div
          class="summary text-sashblack text-sm  mt-sash19 md:mb-sash435 md:mb-sash208 mb-sash363"
        >
          <p>
            Empower prospecting customers to
          </p>
          <p>browse through your product range</p>
          <p>and shop digitally.</p>
        </div>
        <div
          class="flex justify-center items-center mb-10 md:pl-sash538 md:pr-sash528 pl-sash457 pr-sash208 pb-sash363 "
        >
          <!--          <img src="../assets/svg/productmd.svg" alt="" />-->
          <img src="../assets/svg/4.svg" alt="" />
        </div>
      </div>
      <div
        class="card mr-10 ml-10 md:ml-0 md:mr-0 transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer transform lg:-translate-y-24 shadow-lg  rounded-lg bg-white pt-49  text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Fulfilment</h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          The Power of “To go”
        </h4>
        <div
          class="summary text-sashblack text-sm  mt-sash19 md:mb-sash25 mb-sash296"
        >
          <p>
            Fulfil orders as they come in,
          </p>
          <p>while on the move.</p>
        </div>
        <div
          class="flex justify-center items-center mb-10 md:pl-sasash38sh351 md:pr-sash342 pl-sash229 pr-sash203 pb-sash654"
        >
          <!--          <img src="../assets/svg/fulfilmentmd.svg" alt="" />-->
          <img src="../assets/svg/5.svg" alt="" />
        </div>
      </div>
      <div
        class="card  mr-10 ml-10 md:ml-0 md:mr-0 clearfix:after transform transition-all duration-500 ease-in-out  md:hover:scale-105 cursor-pointer md:-translate-y-12 lg:-translate-y-40 shadow-lg  rounded-lg bg-white pt-49  text-center "
      >
        <div class="main font-black text-28 leading-96">
          <h1>Reports</h1>
          <h1>
            Analytics:
          </h1>
        </div>
        <h4 class="text-sashgray text-lg mt-sash6 font-medium  leading-23">
          Your digital business associate
        </h4>
        <div
          class="summary text-sashblack text-sm  mt-sash19 md:mb-sash492 mb-sash347"
        >
          <p>
            Stay on top of your business
          </p>
          <p>numbers at a glance.</p>
        </div>
        <div
          class="flex justify-center items-center mb-10 md:pl-sash631 md:pr-sash635 pl-sash388 pr-sash404 pb-sash444"
        >
          <!--          <img src="../assets/svg/report.svg" alt="" />-->
          <img src="../assets/svg/6.svg" alt="" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import DirtyParticle from "@/components/UIElements/DirtyParticle";
import Particles from "@/components/UIElements/Particles";

export default {
  name: "MainContent",
  components: { Particles, DirtyParticle }
};
</script>

<style scoped lang="scss">
main {
  position: relative;
  //@media screen and (width: 375px) {
  //  margin-top: 12rem;
  //}
  @media screen and (max-width: 767px) {
    background: url("../assets/svg/bendmobile.svg");
  }
  //mobile hero
  @media screen and (min-width: 768px) {
    background-size: cover;
    height: 100%;
    object-fit: cover;
    background: url("../assets/svg/bendmd.svg") no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }
  @media screen and (min-width: 1025px) {
    background: url("../assets/svg/bend.svg");
    object-fit: cover;
  }

  .card-wrapper {
    @media screen and (min-width: 768px) {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      row-gap: 3rem;
      column-gap: 2rem;
      grid-template-areas:
        "header header"
        "col1 col2"
        "col3 col4 "
        "col5 col6";

      .col1 {
        grid-area: col1;
      }
      .col2 {
        grid-area: col2;
      }
      .header {
        grid-area: header;
      }
      .col3 {
        grid-area: col3;
      }
      .col4 {
        grid-area: col4;
      }
      .col5 {
        transform: translateY(0rem);
        grid-area: col5;
      }
      .col6 {
        transform: translateY(-rem);
        grid-area: col6;
      }
    }
    @media screen and (min-width: 1026px) {
      padding-top: 8rem;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      row-gap: 3rem;
      column-gap: 2rem;
      grid-template-areas:
        "col1 col2 header header"
        "col3 col4 col5 col6";

      .col1 {
        grid-area: col1;
      }
      .col2 {
        grid-area: col2;
      }
      .header {
        grid-area: header;
      }
      .col3 {
        grid-area: col3;
      }
      .col4 {
        grid-area: col4;
      }
      .col5 {
        transform: translateY(-5rem);
        grid-area: col5;
      }
      .col6 {
        transform: translateY(-7rem);
        grid-area: col6;
      }
    }
  }
  //.hero {
  //  @media screen and (width: 375px) {
  //    margin-top: -11.5rem;
  //  }
  //}
}
</style>
