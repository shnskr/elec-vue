<template>
  <TopMenu />
  <BodyCanvas />
</template>

<script>
import TopMenu from "@/components/TopMenu";
import BodyCanvas from "@/components/BodyCanvas";

export default {
  name: 'App',
  components: {
    TopMenu,
    BodyCanvas
  }
}
</script>

<style>
html, body, #app {
  height: 100%;
  margin: 0;
}
</style>
