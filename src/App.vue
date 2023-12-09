<template>
  <Greeting />
</template>

<script>
import Greeting from "./components/Greeting.vue";

export default {
  name: "App",
  data() {
    return {
      msg: "Hello World!",
    };
  },
  components: { Greeting },
};
</script>
