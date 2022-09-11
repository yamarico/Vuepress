<template>
  <div>
    <p>Task</p>
    <ul>
      <li v-for="todo of todos" :key="'task'+todo.id">{{ todo.title }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todos: [{ id: 1, title: "sample" }]
    };
  }
};
</script>