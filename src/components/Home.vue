<template>
  <div class="heading">
    <h1>Narendra Singh Rathore</h1>
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
.heading {
  display: flex;
  height: 200px;
  align-items: center;
  justify-content: center;
  font-weight: 1em;
}
h1 {
  font-size: 3em;
}
</style>
