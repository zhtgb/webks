<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  created: function () {
       this.$router.push({ path: "/login"});
    },
  mounted() {},
  beforeDestroy() {},
  methods: {}
};
</script>

<style>
html, body {
    width: 100%;
    height: 100%;
    background: #f0f0f0;
    overflow: hidden;
}
#app {
  width: 100%;
  height: 100%;
}
</style>
