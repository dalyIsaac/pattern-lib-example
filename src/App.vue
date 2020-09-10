<template>
  <div id="app">
    <button-icon icon="chevron-right">
      I am a button with chevron right
    </button-icon>

    <logo size="sm"></logo>
  </div>
</template>

<script>
import { ButtonIcon, Logo } from "@unimelb/pattern-lib-vue";

export default {
  name: "App",
  components: {
    ButtonIcon,
    Logo,
  },
};
</script>

<style>
@import "https://d2glwx35mhbfwf.cloudfront.net/v8.0.1/ui.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: white;
}
</style>
