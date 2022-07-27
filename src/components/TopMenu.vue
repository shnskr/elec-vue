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
      robot.moveMouse(100, 100);
    }
  }
}
</script>

<style scoped>
.container {
  height: 50px;
}
</style>