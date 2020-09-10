<template>
  <div id="app">
    <button-icon icon="chevron-right">I am a button with chevron right</button-icon>

    <check-list>
      <ol slot="list">
        <li>
          Check the
          <a href="a link">degree website</a>.
        </li>
        <li>
          Check the entry requirements to
          <em>clarify</em> your eligibility for application, duplicate instructions after to demonstrate a multiline item-cms: Check the entry requirements to clarify your eligibility for application.
        </li>
        <li>Ensure you meet the University's language requirements.</li>
        <li>Apply online or via the hardcopy application form.</li>
      </ol>
      <a slot="btn" href="/">Continue</a>
    </check-list>
    <logo size="sm"></logo>
  </div>
</template>

<script>
import { ButtonIcon, Logo, CheckList } from "@unimelb/pattern-lib-vue";

export default {
  name: "App",
  components: {
    ButtonIcon,
    Logo,
    CheckList,
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
