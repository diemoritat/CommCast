<script>
import HelloWorld from "./components/HelloWorld";
import Sidebar from "./components/Sidebar";
import GoogleMap from "./components/GoogleMap";

export default {
  name: "App",
  components: {
    HelloWorld,
    Sidebar,
    GoogleMap
  }
};
</script>

<template>
  <div id="app">
    <Sidebar/>
    <google-map
      name="example"
    ></google-map>
  </div>
</template>

<style>
body,
html {
  margin: 0;
  padding: 0;
}
#app {
  background-color: #fff;
  height: 100vh;
  width: 100vw;
  top: 0;
  display: grid;
  grid-template-columns: 30vw 70vw;
  box-sizing: border-box;
  font-family: "Tajawal", sans-serif;
}
</style>
