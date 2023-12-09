<template>
  <button type="button" @click="onClickAge">Increment Age</button>

  <p>The user is {{ age }} years old</p>
</template>

<script>
export default {
  name: "User",
  props: ["age"],
  methods: {
    onClickAge() {
      this.$emit("age-change");
    },
  },
};
</script>
