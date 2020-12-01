<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      A web app for creating a beautifully designed CV in markdown.
      <br />
      Currently in the making.
      <br />
      <a
        href="https://github.com/joshuablum/markdown-cv"
        target="_blank"
        rel="noopener"
        >Check out the source code on GitHub</a
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #ffc600;
}
</style>
