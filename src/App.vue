<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'Hello World'
    };
  }
};
</script>

<style scoped>
#app {
  font-size: 18px;
  font-family: sans-serif;
}
</style>
