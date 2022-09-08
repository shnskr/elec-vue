<template>
  <div class="container">
    <button @click="btnClick" style="height: 100%">button</button>
  </div>
</template>

<script>
const robot = require('robotjs');

export default {
  name: "TopMenu",
  methods: {
    btnClick: function () {
      robot.moveMouseSmooth(100, 100);
    }
  }
}
</script>

<style scoped>
.container {
  height: 50px;
  background: lightgray;
  border-bottom: solid 1px darkgray;
}
</style>