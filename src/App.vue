<template>
  <main>
    <div class="logo">
      <div>NSR</div>
    </div>
    <Home msg="Welcome to Your Vue.js App" />
  </main>
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
html,
body {
  margin: 0;
  font-weight: 1em;
}
main {
  background-color: #dedede;
  display: flex;
  height: 100vh;
  padding: 10px;
  flex-direction: column;
}
.logo {
  border-radius: 50%;
  background-color: black;
  color: white;
  height: 100px;
  width: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 3vh;
}
</style>
