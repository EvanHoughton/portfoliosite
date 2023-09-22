<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>HTML/CSS/JavaScript Project</h3>
    <ul>
      <li><a href="https://github.com/EvanHoughton/SIT1201.2P" target="_blank" rel="noopener">Basic Website</a></li>
    </ul>
    <h3>Vue Projects</h3>
    <ul>
      <li><a href="https://github.com/EvanHoughton/todoapp" target="_blank" rel="noopener">Todo List</a></li>
      <li><a href="https://github.com/EvanHoughton/todoapp/tree/master" target="_blank" rel="noopener">Tic-Tac-Toe</a></li>
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
  color: #8b42b9;
}
</style>
