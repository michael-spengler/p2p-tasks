<template>
  <div>
    <p>{{ todo.title }}</p>
    <button @click="$emit('delete-todo', todo.id)">Delete</button>

  </div>
</template>
<script>
export default {
  name: 'Todo',
  props: [
    "todo"
  ]
}
</script>
<style scoped>
</style>
