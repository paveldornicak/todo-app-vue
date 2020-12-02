<template>
  <div>
    <p>hello from todolist</p>
    <todo-item />
  </div>
</template>

<script>
import TodoItem from "./TodoItem.vue";

export default {
  components: { TodoItem },
};
</script>

<style>
</style>