<template>
  <li v-if="!completed">
    {{ task }}
  </li>
</template>

<script>
  export default {
    name: 'Todo',
    props: [
      'task',
      'completed'
    ]
  }
</script>

<style></style>