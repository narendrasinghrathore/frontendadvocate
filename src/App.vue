<template>
  <div class="main-container">
    <main>
      <section>
        <div aria-label="Logo text" class="logo">
          <div aria-label="Narendra Singh Rathore logo">NSR</div>
        </div>
        <Home msg="Welcome to Your Vue.js App" />
      </section>
    </main>
    <footer>&copy; Narendra Singh Rathore</footer>
  </div>
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
  background-color: #dedede;
}
.main-container {
  display: flex;
  flex-direction: column;
  height: 100vh;
}
main {
  flex: 1;
  padding: 2vw;
  display: flex;
  box-sizing: border-box;
}
section {
  flex-grow: 1;
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
footer {
  border-top: 2px dashed #a5a5a5;
  padding: 4px;
  box-sizing: border-box;
}
</style>
