<template>
  <div id="canvas">

  </div>
</template>

<script>
import BpmnJS from 'bpmn-js';
// const BpmnJS = require('bpmn-js');

const viewer = new BpmnJS({
  container: '#canvas'
});

console.log(viewer);

export default {
  name: "BodyCanvas"
}
</script>

<style scoped>
#canvas {
  height: calc(100% - 51px);
}
</style>