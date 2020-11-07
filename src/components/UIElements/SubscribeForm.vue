<template>
  <form class="h-full w-full grid grid-cols-12" @submit="sendEmail" action="">
    <label
      class="h-full w-full outline-none flex-grow pr-2 col-span-7"
      for="email"
    >
      <input
        id="email"
        v-model="email"
        type="email"
        required
        class="h-full w-full
             text-12 pl-5 md:text-lg outline-none lg:text-base border border-sashborder text-sashgray rounded-full"
        placeholder="Enter your email address"
      />
    </label>
    <input
      @click="sendEmail"
      type="submit"
      value="Get Early Access"
      class="text-12 col-span-4 outline-none md:text-lg lg:text-base font-medium leading-10 font-medium bg-sashgreen text-white rounded-full py-3 pl-2 pr-2 "
    />
  </form>
</template>

<script>
import { serverBus } from "@/main";

export default {
  name: "SubscribeForm",

  data() {
    return {
      email: "",
      errors: []
    };
  },
  methods: {
    sendEmail(e) {
      e.preventDefault();
      this.errors = [];

      if (!this.email) {
        this.errors.push("Email required.");
      } else if (!this.validEmail(this.email)) {
        this.errors.push("Valid email required.");
      } else {
        this.axios
          .post(
            "https://cors-anywhere.herokuapp.com/167.172.137.217/api/mailing-list",
            { email: this.email },
            {
              headers: {
                "Content-Type": "application/json",
                "X-Requested-With": "XMLHttpRequest"
              }
            }
          )
          .then(res => {
            console.log(res);
            serverBus.$emit("showDoneModal", true);
            this.email = "";
          });
        // api.postMailingList(this.email).then(() => console.log("request sent"));
      }
    },
    validEmail: function(email) {
      const re = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
      return re.test(email);
    }
  }
};
</script>

<style scoped lang="scss">
form {
  input[type="email"] {
    &:focus {
      @apply border-2 border-sashgreen;
    }
  }
}
</style>
