<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <quiz-form></quiz-form>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import QuizForm from "./components/QuizForm.vue";
import "./assets/styles/global.css";
export default {
  name: "App",
  components: {
    // HelloWorld,
    QuizForm,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
