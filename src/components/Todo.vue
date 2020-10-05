<template>
  <div>
    <p>{{ todo.title }}</p>
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
