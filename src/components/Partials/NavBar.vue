<template>
  <nav
    class="nav-section lg:flex justify-between items-center  pt-5 md:pt-23 md:pb-23 lg:pl-sash165   md:px-20 md:pr-10s lg:pr-sash165 "
  >
    <div
      class="flex w-full items-center justify-between pb-3 md:pb-0 border-b md:border-b-0 px-sash22 md:px-0"
    >
      <div class="logo " ref="logoSection1">
        <img
          src="../../assets/svg/mobilelogo.svg"
          alt=""
          class="block md:hidden"
        />
        <img
          src="../../assets/svg/mediumlogo.svg"
          alt=""
          class="hidden md:block"
        />
      </div>
      <div
        ref="logoSection2"
        class="nav-toggler bg-sashgray400 lg:hidden rounded-full p-3"
        @click="isNavOpen = !isNavOpen"
      >
        <svg
          width="17"
          height="17"
          viewBox="0 0 17 17"
          fill="none"
          v-if="!isNavOpen"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M2.83337 4.25H14.1667V5.66667H2.83337V4.25ZM2.83337 7.79167H14.1667V9.20833H2.83337V7.79167ZM2.83337 11.3333H14.1667V12.75H2.83337V11.3333Z"
            fill="#231F20"
          />
        </svg>
        <svg
          width="17"
          height="17"
          viewBox="0 0 17 17"
          fill="none"
          v-if="isNavOpen"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M11.2618 4.95825L8.25633 7.963L5.25158 4.95825L4.25 5.95984L7.25475 8.96459L4.25 11.9693L5.25158 12.9709L8.25633 9.96617L11.2618 12.9709L12.2634 11.9693L9.25863 8.96459L12.2634 5.95984L11.2618 4.95825Z"
            fill="#231F20"
          />
        </svg>
      </div>
    </div>
    <div
      ref="smSection"
      class="left-nav hidden lg:flex flex-col lg:flex-row lg:justify-end items-center lg:w-full pt-sash388 lg:pt-0  h-full lg:h-auto h-screen lg:h-auto"
    >
      <a href="#" class="mb-sash22 md:mb-0 ">
        <NavSocialMediaIcon
          ><svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M13.397 20.9969V12.8009H16.162L16.573 9.59191H13.397V7.54791C13.397 6.62191 13.655 5.98791 14.984 5.98791H16.668V3.12691C15.849 3.03891 15.025 2.99691 14.201 2.99991C11.757 2.99991 10.079 4.49191 10.079 7.23091V9.58591H7.332V12.7949H10.085V20.9969H13.397Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a
        href="https://twitter.com/getsash"
        target="_blank"
        class="mb-sash22 md:mb-0"
      >
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M19.633 7.99704C19.646 8.17204 19.646 8.34604 19.646 8.52004C19.646 13.845 15.593 19.981 8.186 19.981C5.904 19.981 3.784 19.32 2 18.172C2.324 18.209 2.636 18.222 2.973 18.222C4.856 18.222 6.589 17.586 7.974 16.501C6.203 16.464 4.719 15.304 4.207 13.708C4.456 13.745 4.706 13.77 4.968 13.77C5.329 13.77 5.692 13.72 6.029 13.633C4.182 13.259 2.799 11.638 2.799 9.68004V9.63004C3.336 9.92904 3.959 10.116 4.619 10.141C3.534 9.41904 2.823 8.18404 2.823 6.78704C2.823 6.03904 3.022 5.35304 3.371 4.75504C5.354 7.19804 8.335 8.79504 11.677 8.97004C11.615 8.67004 11.577 8.35904 11.577 8.04704C11.577 5.82704 13.373 4.01904 15.605 4.01904C16.765 4.01904 17.812 4.50504 18.548 5.29104C19.458 5.11604 20.33 4.77904 21.104 4.31804C20.805 5.25304 20.168 6.03904 19.333 6.53804C20.144 6.45004 20.93 6.22604 21.652 5.91404C21.104 6.71204 20.419 7.42304 19.633 7.99704Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="#" class=" mb-sash22 md:mb-0">
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M20.947 8.30496C20.936 7.54796 20.796 6.79696 20.528 6.08896C20.059 4.87996 19.104 3.92396 17.895 3.45596C17.196 3.19296 16.457 3.05196 15.709 3.03596C14.747 2.99296 14.442 2.98096 12 2.98096C9.55801 2.98096 9.24501 2.98096 8.29001 3.03596C7.54301 3.05196 6.80401 3.19296 6.10501 3.45596C4.89601 3.92396 3.94001 4.87996 3.47201 6.08896C3.20901 6.78796 3.06701 7.52696 3.05301 8.27396C3.01001 9.23696 2.99701 9.54196 2.99701 11.984C2.99701 14.426 2.99701 14.738 3.05301 15.694C3.06801 16.442 3.20901 17.18 3.47201 17.881C3.94101 19.089 4.89601 20.045 6.10601 20.513C6.80201 20.785 7.54101 20.939 8.29101 20.963C9.25401 21.006 9.55901 21.019 12.001 21.019C14.443 21.019 14.756 21.019 15.711 20.963C16.458 20.948 17.197 20.807 17.897 20.544C19.106 20.075 20.061 19.119 20.53 17.911C20.793 17.211 20.934 16.473 20.949 15.724C20.992 14.762 21.005 14.457 21.005 12.014C21.003 9.57196 21.003 9.26196 20.947 8.30496ZM11.994 16.602C9.44001 16.602 7.37101 14.533 7.37101 11.979C7.37101 9.42496 9.44001 7.35596 11.994 7.35596C14.546 7.35596 16.617 9.42496 16.617 11.979C16.617 14.533 14.546 16.602 11.994 16.602ZM16.801 8.26296C16.204 8.26296 15.723 7.78096 15.723 7.18496C15.723 6.58896 16.204 6.10696 16.801 6.10696C17.396 6.10696 17.878 6.58896 17.878 7.18496C17.878 7.78096 17.396 8.26296 16.801 8.26296Z"
              fill="#C3C7CC"
            />
            <path
              d="M11.994 14.9821C13.6525 14.9821 14.997 13.6376 14.997 11.9791C14.997 10.3206 13.6525 8.97607 11.994 8.97607C10.3355 8.97607 8.991 10.3206 8.991 11.9791C8.991 13.6376 10.3355 14.9821 11.994 14.9821Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="#" class="mb-sash22 md:mb-0 ">
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M20 4H4C2.897 4 2 4.897 2 6V18C2 19.103 2.897 20 4 20H20C21.103 20 22 19.103 22 18V6C22 4.897 21.103 4 20 4ZM20 6V6.511L12 12.734L4 6.512V6H20ZM4 18V9.044L11.386 14.789C11.566 14.93 11.783 15 12 15C12.217 15 12.434 14.93 12.614 14.789L20 9.044L20.002 18H4Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="">
        <button
          class="bg-sashgreen h-full text-white rounded-full text-sm leading-18 py-sash12 px-sash40 font-bold"
        >
          Get Sash
        </button>
      </a>
      <p
        class="block absolute bottom-0 pb-sash32 md:hidden text-xs md:text-base lg:text-sm text-thingray font-medium pt-2 pb-10s"
      >
        &copy; 2010 — 2020
        <span class="ml-1">
          <a href="#" class="text-sashgreen">Privacy</a> —
          <a href="#" class="text-sashgreen">Terms</a>
        </span>
      </p>
    </div>
    <div
      v-if="isNavOpen === true"
      class="left-nav  lg:hidden flex flex-col lg:flex-row lg:justify-end items-center w-full pt-sash388 md:pt-10 h-screen"
    >
      <a href="#" class="mb-sash22 md:mb-5 ">
        <NavSocialMediaIcon
          ><svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M13.397 20.9969V12.8009H16.162L16.573 9.59191H13.397V7.54791C13.397 6.62191 13.655 5.98791 14.984 5.98791H16.668V3.12691C15.849 3.03891 15.025 2.99691 14.201 2.99991C11.757 2.99991 10.079 4.49191 10.079 7.23091V9.58591H7.332V12.7949H10.085V20.9969H13.397Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a
        href="https://twitter.com/getsash"
        target="_blank"
        class="mb-sash22 md:mb-5"
      >
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M19.633 7.99704C19.646 8.17204 19.646 8.34604 19.646 8.52004C19.646 13.845 15.593 19.981 8.186 19.981C5.904 19.981 3.784 19.32 2 18.172C2.324 18.209 2.636 18.222 2.973 18.222C4.856 18.222 6.589 17.586 7.974 16.501C6.203 16.464 4.719 15.304 4.207 13.708C4.456 13.745 4.706 13.77 4.968 13.77C5.329 13.77 5.692 13.72 6.029 13.633C4.182 13.259 2.799 11.638 2.799 9.68004V9.63004C3.336 9.92904 3.959 10.116 4.619 10.141C3.534 9.41904 2.823 8.18404 2.823 6.78704C2.823 6.03904 3.022 5.35304 3.371 4.75504C5.354 7.19804 8.335 8.79504 11.677 8.97004C11.615 8.67004 11.577 8.35904 11.577 8.04704C11.577 5.82704 13.373 4.01904 15.605 4.01904C16.765 4.01904 17.812 4.50504 18.548 5.29104C19.458 5.11604 20.33 4.77904 21.104 4.31804C20.805 5.25304 20.168 6.03904 19.333 6.53804C20.144 6.45004 20.93 6.22604 21.652 5.91404C21.104 6.71204 20.419 7.42304 19.633 7.99704Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="#" class=" mb-sash22 md:mb-5">
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M20.947 8.30496C20.936 7.54796 20.796 6.79696 20.528 6.08896C20.059 4.87996 19.104 3.92396 17.895 3.45596C17.196 3.19296 16.457 3.05196 15.709 3.03596C14.747 2.99296 14.442 2.98096 12 2.98096C9.55801 2.98096 9.24501 2.98096 8.29001 3.03596C7.54301 3.05196 6.80401 3.19296 6.10501 3.45596C4.89601 3.92396 3.94001 4.87996 3.47201 6.08896C3.20901 6.78796 3.06701 7.52696 3.05301 8.27396C3.01001 9.23696 2.99701 9.54196 2.99701 11.984C2.99701 14.426 2.99701 14.738 3.05301 15.694C3.06801 16.442 3.20901 17.18 3.47201 17.881C3.94101 19.089 4.89601 20.045 6.10601 20.513C6.80201 20.785 7.54101 20.939 8.29101 20.963C9.25401 21.006 9.55901 21.019 12.001 21.019C14.443 21.019 14.756 21.019 15.711 20.963C16.458 20.948 17.197 20.807 17.897 20.544C19.106 20.075 20.061 19.119 20.53 17.911C20.793 17.211 20.934 16.473 20.949 15.724C20.992 14.762 21.005 14.457 21.005 12.014C21.003 9.57196 21.003 9.26196 20.947 8.30496ZM11.994 16.602C9.44001 16.602 7.37101 14.533 7.37101 11.979C7.37101 9.42496 9.44001 7.35596 11.994 7.35596C14.546 7.35596 16.617 9.42496 16.617 11.979C16.617 14.533 14.546 16.602 11.994 16.602ZM16.801 8.26296C16.204 8.26296 15.723 7.78096 15.723 7.18496C15.723 6.58896 16.204 6.10696 16.801 6.10696C17.396 6.10696 17.878 6.58896 17.878 7.18496C17.878 7.78096 17.396 8.26296 16.801 8.26296Z"
              fill="#C3C7CC"
            />
            <path
              d="M11.994 14.9821C13.6525 14.9821 14.997 13.6376 14.997 11.9791C14.997 10.3206 13.6525 8.97607 11.994 8.97607C10.3355 8.97607 8.991 10.3206 8.991 11.9791C8.991 13.6376 10.3355 14.9821 11.994 14.9821Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="#" class="mb-sash22 md:mb-5 ">
        <NavSocialMediaIcon>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M20 4H4C2.897 4 2 4.897 2 6V18C2 19.103 2.897 20 4 20H20C21.103 20 22 19.103 22 18V6C22 4.897 21.103 4 20 4ZM20 6V6.511L12 12.734L4 6.512V6H20ZM4 18V9.044L11.386 14.789C11.566 14.93 11.783 15 12 15C12.217 15 12.434 14.93 12.614 14.789L20 9.044L20.002 18H4Z"
              fill="#C3C7CC"
            />
          </svg>
        </NavSocialMediaIcon>
      </a>
      <a href="">
        <button
          class="bg-sashgreen h-full text-white rounded-full text-sm leading-18 py-sash12 px-sash40 font-bold"
        >
          Get Sash
        </button>
      </a>
      <p
        class="block absolute bottom-0 pb-sash32 md:hidden text-xs md:text-base lg:text-sm text-thingray font-medium pt-2 pb-10s"
      >
        &copy; 2010 — 2020
        <span class="ml-1">
          <a href="#" class="text-sashgreen">Privacy</a> —
          <a href="#" class="text-sashgreen">Terms</a>
        </span>
      </p>
    </div>
  </nav>
</template>

<script>
// import { gsap } from "gsap";
import NavSocialMediaIcon from "../UIElements/NavSocialMediaIcon";

export default {
  name: "NavBar",
  mounted() {
    // const NavTl = new TweenMax();
    // const { logoSection } = this.$refs;
    //
    // NavTl.to(logoSection, 1, { y: 50, autoAlpha: 0 });
    //
    // const { logoSection1, logoSection2, smSection } = this.$refs;
    //
    // gsap.from([logoSection1, logoSection2, smSection], 1, {
    //   y: -200
    //   // ease: Power1.easeInOut
    // });
  },
  data() {
    return {
      isNavOpen: false
    };
  },
  components: { NavSocialMediaIcon }
};
</script>

<style scoped lang="scss">
.nav-section {
  @media screen and (min-width: 1367px) {
    padding-left: 20rem;
    padding-right: 20rem;
  }
  @media screen and (min-width: 1467px) {
    padding-left: 15rem;
    padding-right: 15rem;
  }
}
</style>
