<template>
  <div id="app">
    <add-todo></add-todo>
    <filter-todos></filter-todos>
   <todos/>
  </div>
</template>

<script>
import Todos from "@/components/Todos";
import AddTodo from "@/components/AddTodo";
import FilterTodos from "@/components/FilterTodos";

export default {
  name: 'App',
  components: {
    FilterTodos,
    Todos, AddTodo
  }
}
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
