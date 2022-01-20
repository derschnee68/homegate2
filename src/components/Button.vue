<template>
  <button>{{msg}}</button>
</template>

<script>
export default {
  name: "Button",
  props: {
    msg: String,
  },
};
</script>

<style>
button {
  background: red;
  color: white;
}
</style>