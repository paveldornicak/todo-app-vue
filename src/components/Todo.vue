<template>
  <div>
    <h1>Todo App</h1>
    <todo-list />
    <create-todo />
  </div>
</template>

<script>
import CreateTodo from "./CreateTodo.vue";
import TodoList from "./TodoList.vue";

export default {
  name: "Todo",
  components: { CreateTodo, TodoList },
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
  color: #42b983;
}
</style>
