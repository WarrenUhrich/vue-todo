<template>
  <section>
    <h2>To-Do List</h2>
    <ul>

    </ul>
  </section>
</template>

<script>
  export default {
    name: 'TodoList',
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