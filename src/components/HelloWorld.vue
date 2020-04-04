<template>
  <h1>{{greeting}}</h1>
</template>

<script>

export default {
  name: 'HelloWorld',
  props: {
    greeting: {
      type: String,
      default: 'Hello World'
    }
  },
  data() {
    return {};
  },
};
</script>

<style scoped lang="scss">
$primary-color: white;
$bg: black;
h1 {
  color: $primary-color;
  background-color: $bg;
}
</style>

