<template>
  <div id="app">
    <art-board />
  </div>
</template>

<script>
import ArtBoard from "./components/ArtBoard";

export default {
  name: "App",
  components: {
    ArtBoard
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html,
body {
  width: 100%;
  height: 100%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
