<script setup>
// setup is syntactic sugar for composition API
// that is, you don't need to use `export default{ setup() {...}}`
import TodoForm from './TodoForm.vue'
import TodoList from './TodoList.vue'
</script>

<template>
<div class="todo-app">
    <h1>To Do List</h1>
    <todo-form />
    <todo-list />
</div>
</template>

<style scoped>

</style>