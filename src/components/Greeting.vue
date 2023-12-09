<template>
  <p>{{ greeting }}</p>
</template>

<script>
export default {
  name: "Greeting",
  data() {
    return {
      greeting: "Hello, my name is Ben.",
    };
  },
};
</script>
