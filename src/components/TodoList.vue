<template>
  <section>
    <h2>To-Do List</h2>
    <ul>
      <Todo v-for="todo in todos" :key="todo.task" :task="todo.task" />
    </ul>
  </section>
</template>

<script>
  import Todo from './Todo.vue';

  export default {
    name: 'TodoList',
    components: {
      Todo
    },
    data () {
      return {
        todos: [
          {
            task: 'Buy Milk',
            completed: false
          },
          {
            task: 'Pick up Prescription',
            completed: false
          },
          {
            task: 'Study Vue',
            completed: false
          },
          {
            task: 'Install Visual Studio Code',
            completed: false
          }
        ]
      }
    }
  }
</script>

<style>
</style>