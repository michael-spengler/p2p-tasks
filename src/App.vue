<template>
  <div id="app">
    <Todos v-bind:todos="todos" />
  </div>
</template>
<script>

import Todos from "./components/Todos.vue";
export default {
  name: "app",
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Go workout",
          completed: false
        },
        {
          id: 2,
          title: "Do laundry",
          completed: false
        },
        {
          id: 3,
          title: "Cook food",
          completed: false
        },
        {
          id: 4,
          title: "Clean up room",
          completed: false
        },
        {
          i: 5,
          title: "Finish work",
          completed: false
        }
      ]
    };
  }
};
</script>
<style>
</style>