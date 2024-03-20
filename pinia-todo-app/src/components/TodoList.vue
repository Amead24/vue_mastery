<script setup>
import { useTodoListStore } from '@/stores/todoList';
import { storeToRefs } from 'pinia';

const store = useTodoListStore()

// create references to each element in store data
const { todoList } = storeToRefs(store)
</script>

<template>
<div v-for="todo in todoList" :key="todo.id" class="item">
    <div class="content">
        <span>{{ todo.item }}</span>
    </div>
</div>
</template>

<style scoped>

</style>