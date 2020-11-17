<template>
  <section>
    <div class="">
      <!--      <NavBar class="sticky top-0 bg-white z-50"></NavBar>-->
      <header
        class="h-auto md:h-screen lg:pl-sash165 md:pl-10  md:px-0 md:pr-10 lg:pr-sash165 "
      >
        <div
          class="header-image absolute  right-0 lg:top-0 lg:mt-24 hidden lg:blocks lg:hidden z-10 lg:mr-7"
        >
          <img
            src="../assets/images/Header-image.png"
            alt="Header Image"
            class="z-30 hidden lg:block"
          />
          <img
            src="../assets/images/Header-image.png"
            alt="Header Image"
            class="z-50 block md:hidden"
          />
        </div>
        <main
          class="hero-text-section relative   h-auto md:h-90vh font-serif lg:flexs lg:justify-between flex-wraps lg:grid lg:grid-cols-12  lg:items-center px-5 md:px-0"
        >
          <div
            class="heading z-10 md:col-span-7 lg:text-justify text-center  md:pt-20 pt-sash29 lg:-mt-24  mb-10 md:mb-0 lg:self-centers "
          >
            <div
              class="main-text text-sashblack text-mobiletext md:text-35 md:text-48px md:leading-112  ip:text-6xls font-black leading-tight"
            >
              <h1 ref="text1" class="text1">A modern social</h1>
              <h2 ref="text2" class="text2"><span>commerce</span> app.</h2>
            </div>
            <div
              ref="text3"
              class=" text3 sub-text md:max-w-2xl  text-sm leading-18 md:leading-30  text-sashgray md:text-summobile md:text-summobile mt-3 md:mt-sash12 md:mt-sash133"
            >
              <p>
                Sash is a new way for customers to direct message,
              </p>
              <p>order from and pay merchants in a fun,</p>
              <p>fast and seamless way.</p>
            </div>

            <div
              ref="item4"
              class="item4 download-options flex items-center justify-center lg:justify-start mt-3 md:mt-8"
            >
              <a
                href="#"
                class="transform hover:scale-125 transition-all duration-100"
              >
                <img class="mr-4" src="../assets/svg/ios.svg" alt=""
              /></a>
              <a
                href="#"
                class="transform hover:scale-125 transition-all duration-100"
              >
                <img src="../assets/svg/googleplay.svg" alt=""
              /></a>
            </div>
          </div>
          <div
            class="herosection col-span-5  image-wrapper flex lg:self-center -ml-3 lg:absolute pl-10 top-0s right-0 lg:-mr-12 md:mt-16 lg:mt-0 bg-white"
          >
            <img
              ref="heroImg1"
              src="../assets/images/Header-image.png"
              alt="Header Image"
              class="z-30 hero-img hidden  lg:block h-auto"
            />

            <img
              ref="heroImg2"
              src="../assets/images/Header-image.png"
              alt="Header Image"
              class="mobile-hero hero-img  h-auto object-cover object-top hidden md:block lg:hidden md:w-card z-20 md:mx-auto "
            />
            <img
              ref="heroImg3"
              src="../assets/images/mobilehero.png"
              alt="Header Image"
              class="mobile-hero hero-img h-auto object-cover object-top block md:hidden z-20 mx-auto  "
            />
          </div>
        </main>
        <div class="mobile-svg "></div>
      </header>
      <!--    </div>-->
      <section
        class="main-content relative h-full w-full pt-27 pb-10 md:pb-48 -mt-56s -mt-bgtop md:-mt-bgtopmd lg:-mt-bgtoplg"
      >
        <div class="top">
          <div class="stroke w-full flex justify-center items-center">
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
              width="50"
              height="8"
              viewBox="0 0 50 8"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="50" height="8" rx="4" fill="#30C684" />
            </svg>
          </div>

          <h1
            class="text-xl leading-25 md:text-40px md:leading-sub text-sashblack text-center font-black mt-sash11 "
          >
            What can you do with Sash?
          </h1>
          <p
            class="text-sm leading-18 md:text-2xl md:leading-30 text-center text-sashgray200 px-16 max-w-5xl md:max-w-2xl mx-auto mt-3"
          >
            Convert faster and improve productivity when you move your business
            conversations over from social media DMs.
          </p>
        </div>
        <main class="mt-69">
          <div
            class="tile-1 w-full flex flex-col mb-91 md:mb-0  md:justify-center items-center md:grid grid-cols-12"
          >
            <div
              class="image-wrapper lg:flex justify-center items-center col-span-6  md:items-center order-2 md:order-1 md:mr-7s lg"
            >
              <img
                class="hidden gif-lg md:block ml-auto  md:mr-16"
                src="../assets/images/giffile.gif"
                alt=""
              />
              <img
                class="block gif-lg md:hidden mx-auto"
                src="../assets/images/giffile.gif"
                alt=""
              />
            </div>
            <div class="tile-text text-left col-span-6 order-1 md:order-2">
              <svg
                width="39"
                height="36"
                viewBox="0 0 39 36"
                fill="none"
                class="mx-auto md:mx-0"
                xmlns="http://www.w3.org/2000/svg"
              >
                >
                <path
                  d="M24.6154 8.69226H4.92308C3.56554 8.69226 2.46154 9.79626 2.46154 11.1538V25.923C2.46154 27.2806 3.56554 28.3846 4.92308 28.3846H8.61538V33.0209L16.3409 28.3846H24.6154C25.9729 28.3846 27.0769 27.2806 27.0769 25.923V11.1538C27.0769 9.79626 25.9729 8.69226 24.6154 8.69226ZM24.6154 25.923H15.6591L11.0769 28.6713V25.923H4.92308V11.1538H24.6154V25.923Z"
                  fill="black"
                />
                <path
                  d="M8.61538 14.8461H20.9231V17.3076H8.61538V14.8461ZM8.61538 19.7691H17.2308V22.2307H8.61538V19.7691Z"
                  fill="black"
                />
              </svg>
              <p
                class="tag-line uppercase text-center md:text-left text-sashgray text-10 md:text-lg leading-25 mt-sash12"
              >
                DO MORE WITH DIRECT MESSAGING
              </p>
              <h1
                class="title text-sashblack text-xl leading-24 md:text-30px md:leading-36 text-center md:text-left font-black  md:mt-sash10 px-16 md:px-0 md:max-w-xs"
              >
                Conversational Commerce
              </h1>
              <p
                class="summary text-sashgray200 text-sm md:text-lg text-center md:text-left leading-20 md:leading-25 mt-sash10 mx-auto md:mx-0 max-w-xs"
              >
                Delight your customers with a seamless messaging, ordering,
                check-out and payment experience.
              </p>
            </div>
          </div>
          <div
            class="tile-2 mt-8s w-full mb-91 md:mb-0 flex flex-col justify-center items-center md:grid grid-cols-12"
          >
            <div
              class="tile-text text-right  justify-self-end col-span-6 md:mr-8"
            >
              <div class="icon flex justify-end">
                <svg
                  width="39"
                  height="36"
                  viewBox="0 0 39 36"
                  fill="none"
                  class="mx-auto md:mx-0"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle
                    cx="27.3077"
                    cy="11.9231"
                    r="11.6923"
                    fill="#30C684"
                  />
                  <path
                    d="M14.1539 32.0781H16.6154C16.6154 24.6123 10.5415 18.5385 3.07693 18.5385V21C9.184 21 14.1539 25.9698 14.1539 32.0781Z"
                    fill="black"
                  />
                  <path
                    d="M9.23077 32.0782H11.6923C11.6923 27.3274 7.8277 23.4615 3.07693 23.4615V25.9231C6.47016 25.9231 9.23077 28.6837 9.23077 32.0782Z"
                    fill="black"
                  />
                  <path
                    d="M4.92308 32.077C5.94268 32.077 6.76924 31.2504 6.76924 30.2308C6.76924 29.2112 5.94268 28.3846 4.92308 28.3846C3.90348 28.3846 3.07693 29.2112 3.07693 30.2308C3.07693 31.2504 3.90348 32.077 4.92308 32.077Z"
                    fill="black"
                  />
                  <path
                    d="M25.2308 11.1539H5.53847C4.18093 11.1539 3.07693 12.2579 3.07693 13.6154V16.1409C3.91385 16.1717 4.73723 16.2566 5.53847 16.408V13.6154H25.2308V29.6154H18.7458C18.8972 30.4166 18.9809 31.24 19.0129 32.0769H25.2308C26.5883 32.0769 27.6923 30.9729 27.6923 29.6154V13.6154C27.6923 12.2579 26.5883 11.1539 25.2308 11.1539Z"
                    fill="black"
                  />
                </svg>
              </div>
              <p
                class="tag-line uppercase text-center md:text-right text-sashgray text-10 md:text-lg leading-25 mt-sash12"
              >
                GROW ORGANICALLY
              </p>
              <h1
                class="title text-sashblack text-xl leading-24 md:text-30px md:leading-36 text-center md:text-right font-black md:mt-sash10 px-32 md:px-0 md:max-w-xs"
              >
                Social Discovery
              </h1>
              <p
                class="summary text-sashgray200 text-sm md:text-lg text-center md:text-right leading-20 md:leading-25 mt-sash10 mx-auto px-2 md:mx-0 max-w-xs"
              >
                A new way for your customers and their friends to discover and
                promote your business & products.
              </p>
            </div>
            <div
              class="image-wrapper col-span-6 md:justify-self-start md:-ml-10 lg:ml-0"
            >
              <img
                class="hidden md:block "
                src="../assets/images/tile2.png"
                alt=""
              />
              <img
                class="block md:hidden mx-auto"
                src="../assets/images/tile2mobile.png"
                alt=""
              />
            </div>
          </div>
          <div
            class="tile-3 w-full mb-91 md:mb-0 flex flex-col justify-center items-center md:grid grid-cols-12"
          >
            <div
              class="image-wrapper col-span-6 justify-self-end order-2 md:order-1 md:mr-7s"
            >
              <img
                class="hidden md:block ml-auto  md:mr-16"
                src="../assets/images/tile3.png"
                alt=""
              />
              <img
                class="block md:hidden mx-auto"
                src="../assets/images/tile3mobile.png"
                alt=""
              />
            </div>
            <div class="tile-text text-left col-span-6 order-1 md:order-2">
              <svg
                width="39"
                height="36"
                viewBox="0 0 39 36"
                fill="none"
                class="mx-auto md:mx-0"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="26.6923" cy="11.9231" r="11.6923" fill="#00BEFF" />
                <path
                  d="M6.15385 33.3077H23.3846C24.7422 33.3077 25.8462 32.2037 25.8462 30.8462V17.3077C25.8462 16.6271 25.296 16.0769 24.6154 16.0769H20.9231V14.8462C20.9231 11.4529 18.1625 8.69231 14.7692 8.69231C11.376 8.69231 8.61538 11.4529 8.61538 14.8462V16.0769H4.92308C4.24246 16.0769 3.69231 16.6271 3.69231 17.3077V30.8462C3.69231 32.2037 4.79631 33.3077 6.15385 33.3077ZM11.0769 14.8462C11.0769 12.8105 12.7335 11.1539 14.7692 11.1539C16.8049 11.1539 18.4615 12.8105 18.4615 14.8462V16.0769H11.0769V14.8462ZM6.15385 18.5385H8.61538V21H11.0769V18.5385H18.4615V21H20.9231V18.5385H23.3846L23.3871 30.8462H6.15385V18.5385Z"
                  fill="black"
                />
              </svg>

              <p
                class="tag-line uppercase text-center md:text-left text-sashgray text-10 md:text-lg leading-25 mt-sash12"
              >
                SHOWCASE YOUR HUSTLE
              </p>
              <h1
                class="title text-sashblack text-xl leading-24 md:text-30px md:leading-36 text-center md:text-left font-black md:mt-sash10 px-16 md:px-0 md:max-w-xs"
              >
                Product Catalogue
              </h1>
              <p
                class="summary text-sashgray200 text-sm md:text-lg text-center md:text-left leading-20 md:leading-25 mt-sash10 mx-auto md:mx-0 max-w-xs"
              >
                Empower prospecting customers to browse through your product
                range and shop digitally.
              </p>
            </div>
          </div>
          <div
            class="tile-4 w-full mb-91 md:mb-0 flex flex-col justify-center items-center md:grid grid-cols-12"
          >
            <div
              class="tile-text text-right  justify-self-end col-span-6 md:mr-8"
            >
              <div class="icon flex justify-end">
                <svg
                  width="39"
                  height="37"
                  viewBox="0 0 39 37"
                  fill="none"
                  class="mx-auto md:mx-0"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle
                    cx="27.3077"
                    cy="12.4231"
                    r="11.6923"
                    fill="#00BEFF"
                  />
                  <path
                    d="M25.2308 10.4231H5.53847C4.18093 10.4231 3.07693 11.5271 3.07693 12.8846V15.3462C3.07693 16.252 3.57539 17.0385 4.3077 17.4656V30.1154C4.3077 31.4729 5.4117 32.5769 6.76924 32.5769H24C25.3575 32.5769 26.4615 31.4729 26.4615 30.1154V17.4656C27.1939 17.0385 27.6923 16.252 27.6923 15.3462V12.8846C27.6923 11.5271 26.5883 10.4231 25.2308 10.4231ZM5.53847 12.8846H25.2308L25.2332 15.3462H25.2308H5.53847V12.8846ZM6.76924 30.1154V17.8077H24L24.0025 30.1154H6.76924Z"
                    fill="black"
                  />
                  <path
                    d="M10.4615 20.2692H20.3077V22.7308H10.4615V20.2692Z"
                    fill="black"
                  />
                </svg>
              </div>
              <p
                class="tag-line uppercase text-center md:text-right text-sashgray text-10 md:text-lg leading-25 mt-sash12"
              >
                THE POWER OF “TO GO”
              </p>
              <h1
                class="title text-sashblack text-xl leading-24 md:text-30px md:leading-36 text-center md:text-right font-black md:mt-sash10 px-32 md:px-0 md:max-w-xs"
              >
                Fulfilment
              </h1>
              <p
                class="summary text-sashgray200 text-sm md:text-lg text-center md:text-right leading-20 md:leading-25 mt-sash10 mx-auto px-20 md:px-0 md:mx-0 md:max-w-xs"
              >
                Fulfil orders as they coming in while on the move
              </p>
            </div>
            <div
              class="image-wrapper col-span-6 justify-self-start md:-ml-10 lg:ml-0"
            >
              <img
                class="hidden md:block"
                src="../assets/images/tile4.png"
                alt=""
              />
              <img
                class="block md:hidden mx-auto"
                src="../assets/images/tile4mobile.png"
                alt=""
              />
            </div>
          </div>
          <div
            class="tile-5 w-full mb-91 md:mb-0 flex flex-col justify-center items-center md:grid grid-cols-12"
          >
            <div
              class="image-wrapper col-span-6 justify-self-end  order-2 md:order-1 md:mr-7s"
            >
              <img
                class="hidden md:block ml-auto  md:mr-16"
                src="../assets/images/tile5.png"
                alt=""
              />
              <img
                class="block md:hidden mx-auto"
                src="../assets/images/tile5mobile.png"
                alt=""
              />
            </div>
            <div class="tile-text text-left col-span-6 order-1 md:order-2">
              <svg
                width="39"
                height="37"
                viewBox="0 0 39 37"
                fill="none"
                class="mx-auto md:mx-0"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="26.6923" cy="12.423" r="11.6923" fill="#00BEFF" />
                <path
                  d="M14.7692 9.19226C7.98277 9.19226 2.46154 14.7135 2.46154 21.5C2.46154 28.2864 7.98277 33.8076 14.7692 33.8076C21.5557 33.8076 27.0769 28.2864 27.0769 21.5C27.0769 14.7135 21.5557 9.19226 14.7692 9.19226ZM24.5305 20.2692H16V14.1153V11.7387C20.4443 12.2963 23.9729 15.8249 24.5305 20.2692ZM4.92308 21.5C4.92308 16.4883 8.69046 12.348 13.5385 11.7387V14.1153V21.5C13.5385 21.6464 13.5729 21.788 13.6234 21.9246C13.6394 21.964 13.6554 22.0009 13.6751 22.039C13.6935 22.076 13.7022 22.1166 13.7255 22.1535L18.8972 30.428C17.6394 31.0113 16.2437 31.3461 14.7692 31.3461C9.34031 31.3461 4.92308 26.9289 4.92308 21.5ZM20.9871 29.1258L16.9908 22.7307H24.5305C24.208 25.2993 22.8985 27.5652 20.9871 29.1258Z"
                  fill="black"
                />
              </svg>

              <p
                class="tag-line uppercase text-center md:text-left text-sashgray text-10 md:text-lg leading-25 mt-sash12"
              >
                YOUR DIGITAL BUSINESS ASSOCIATE
              </p>
              <h1
                class="title text-sashblack text-xl leading-24 md:text-30px md:leading-36 text-center md:text-left font-black md:mt-sash10 px-16 md:px-0 md:max-w-xs"
              >
                Report & Analytics
              </h1>
              <p
                class="summary text-sashgray200 text-sm md:text-lg text-center md:text-left leading-20 md:leading-25 mt-sash10 mx-auto md:mx-0 max-w-xs"
              >
                Stay on top of your business numbers at a glance.
              </p>
            </div>
          </div>
        </main>
      </section>
    </div>
  </section>
</template>

<script>
// import { gsap, Power1 } from "gsap";
export default {
  name: "Index",
  mounted() {
    // const {
    //   text1,
    //   text2,
    //   text3,
    //   item4,
    //   heroImg1,
    //   heroImg2,
    //   heroImg3
    // } = this.$refs;
    //
    // gsap.fromTo(
    //   [heroImg1, heroImg2, heroImg3],
    //   {
    //     x: 400,
    //     ease: Power1.easeInOut
    //   },
    //   {
    //     x: 0,
    //     ease: Power1.easeInOut,
    //     duration: 1
    //   }
    // );
    // gsap.fromTo(
    //   text1,
    //   {
    //     y: 200,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 0
    //   },
    //   {
    //     y: 0,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 1,
    //     duration: 2
    //   }
    // );
    // gsap.fromTo(
    //   text2,
    //   {
    //     y: 200,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 0
    //   },
    //   {
    //     y: 0,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 1,
    //     delay: 1,
    //     duration: 1.5
    //   }
    // );
    // gsap.fromTo(
    //   text3,
    //   {
    //     y: 200,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 0
    //   },
    //   {
    //     y: 0,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 1,
    //     delay: 1.5,
    //     duration: 1.5
    //   }
    // );
    // gsap.fromTo(
    //   item4,
    //   {
    //     y: 200,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 0
    //   },
    //   {
    //     y: 0,
    //     ease: Power1.easeInOut,
    //     autoAlpha: 1,
    //     delay: 2,
    //     duration: 1.5
    //   }
    // );
  },
  components: {}
};
</script>

<style scoped lang="scss">
section {
  img {
    max-width: 100%;
    height: auto;
  }
  header {
    @media screen and (min-width: 1367px) {
      padding-left: 20rem;
      padding-right: 20rem;
    }
    @media screen and (min-width: 1400px) {
      padding-left: 15rem;
      padding-right: 15rem;
    }
    @media screen and (min-width: 1467px) {
      padding-left: 15rem;
      padding-right: 15rem;
    }
  }
  main {
    //height: 90vh;
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
      @media screen and (max-width: 900px) {
        width: 9rem;
        margin: -2px auto;
        height: 7px;
        display: none;
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

    //.image-wrapper {
    //  width: 100%;
    //  margin: 0 auto;
    //
    //  .mobile-hero {
    //    width: 100%;
    //    height: auto;
    //  }
    //}
  }
  .main-content {
    position: relative;

    @media screen and (max-width: 767px) {
      background-size: cover;
      height: 100%;
      object-fit: cover;
      background: url("../assets/svg/mobilebg.svg");
      -webkit-background-size: cover;
      -moz-background-size: cover;
      -o-background-size: cover;
      background-repeat: no-repeat;
      .gif-lg {
        margin-top: 20px;
        width: 157px !important;
        height: 285px !important;
      }
    }
    //mobile hero
    @media screen and (min-width: 768px) {
      background-size: cover;
      height: 100%;
      object-fit: cover;
      background: url("../assets/svg/bg.svg");
      -webkit-background-size: cover;
      -moz-background-size: cover;
      -o-background-size: cover;
      .gif-lg {
        width: 255px !important;
        height: 502px !important;
      }
      //background-repeat: no-repeat;
    }
    @media screen and (min-width: 1025px) {
      background-size: cover;
      background-repeat: no-repeat;
      background: url("../assets/svg/bg.svg");
      object-fit: cover;
      -webkit-background-size: cover;
      -moz-background-size: cover;
      -o-background-size: cover;
      .gif-lg {
        width: 255px !important;
        height: 502px !important;
      }
    }
    @media screen and (min-width: 1367px) {
      margin-top: -25rem;
      background-size: cover;
      background-repeat: no-repeat;
      background: url("../assets/svg/bg.svg");
      object-fit: cover;
      -webkit-background-size: cover;
      -moz-background-size: cover;
      -o-background-size: cover;
    }
    @media screen and (min-width: 1467px) {
      margin-top: -26rem;
    }

    //.hero {
    //  @media screen and (width: 375px) {
    //    margin-top: -11.5rem;
    //  }
    //}
  }
}
</style>
