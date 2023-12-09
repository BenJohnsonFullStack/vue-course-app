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

<style scoped>
p {
  background-color: #1c1c1c;
  color: #dcdcdc;
}
</style>
