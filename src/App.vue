<template>
  <CalculatorView />
</template>

<script>
import CalculatorView from "./components/CalculatorView.vue";

export default {
  name: "App",
  components: {
    CalculatorView,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Roboto, sans-serif;
  text-align: center;
  color: #2c3e50;
  background-image: url(./assets/images/bubor5.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  height: 100vh;
}
</style>
