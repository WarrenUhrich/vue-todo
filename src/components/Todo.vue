<template>
  <li>
    {{ task }}
  </li>
</template>

<script>
  export default {
    name: 'Todo',
    props: [
      'task'
    ]
  }
</script>

<style></style>