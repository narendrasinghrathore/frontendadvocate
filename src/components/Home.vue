<template>
  <div class="container">
    <section class="flex">
      <div class="img"></div>
      <div class="heading">
        <h1>Narendra Singh Rathore</h1>
      </div>
    </section>
    <section>
      <p class="info">
        You can connect with me:
        <span class="email">
          <a href="mailto:nsrathore0212@gmail.com"
            >nsrathore0212@gmail.com</a
          ></span
        >
      </p>
      <p class="info">
        Follow me on github:
        <a href="https://github.com/narendrasinghrathore"
          >https://github.com/narendrasinghrathore</a
        >
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  position: relative;
  font-size: 1em;
  display: flex;
  flex-direction: column;
}
section.flex {
  display: flex;
  flex-wrap: wrap;
}
.img {
  background: url("../assets/home-image.svg") no-repeat center;
  height: 40vh;
  background-size: contain;
  border: none;
  outline: none;
  min-width: 46vw;
  flex-grow: 1;
}
.heading {
  top: 0;
  left: 0;
  right: 0;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-grow: 1;
  min-width: 46vw;
}
h1 {
  font-size: 3em;
}
.info {
  font-size: 1.5em;
}

.email {
  background-color: rgb(158, 158, 158);
  color: white;
  padding: 2px 4px ;
  border-radius: 3px;
  text-decoration: none;  
}
a{
  text-decoration: none;
  color:inherit;
}
</style>
