<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Mon site est en construction </h2>
    <img alt="Landing under construction" src="../assets/landing.png">
    <h3>Liens</h3>
    <ul>
      <li><a href="https://twitter.com/elienairo" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://github.com/lxyflorian" target="_blank" rel="noopener">Github</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
  font-weight: 700;
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
  color: #ff0000;
}
</style>
