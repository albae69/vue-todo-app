<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <filterTodos />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos';
import AddTodo from './components/addTodo';
import filterTodos from './components/filterTodos';
export default {
  name: 'app',
  components: {
    Todos,
    AddTodo,
    filterTodos
  }
};
</script>

<style>
body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #c8f8f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
