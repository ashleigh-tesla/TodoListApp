<template>
<div id="app">
  <todo-list-app></todo-list-app>
</div>
</template>

<script>
import TodoListApp from './components/TodoListApp.vue'

export default {
  name: 'App',
  components: {
    TodoListApp
  }
}
</script>