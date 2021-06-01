<template>
  <div class="container mx-auto px-4">
    <Header text="Todo App" />
    <Button @click="buttonClick()" />
  </div>
</template>

<script>
import Header from "./components/Header";
import Button from "./components/Button";

export default {
  name: "App",
  components: {
    Header,
    Button,
  },
  methods: {
    buttonClick() {
      alert("helo");
    },
  },
};
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
