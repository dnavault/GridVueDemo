<template>
  <div>
    <h2>{{ title }}</h2>
  </div>
</template>

<script>
export default {
  name: "GridVue",
  props: {
    title: String,
  },
};
</script>

<style scoped>
h2 {
  margin: 40px 0 0;
}
</style>
