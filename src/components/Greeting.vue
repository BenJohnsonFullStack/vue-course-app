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

<style scoped lang="scss">
p:hover {
  color: darken(#cc4444, 15%);
}
</style>
