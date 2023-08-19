<script setup>
      import ChildComponent from './components/ChildComponent.vue'  
      import { ref } from 'vue';
      const message  = ref("Hello from parent!");
</script>

<template>
    <h2>Parent Component</h2>
    <ChildComponent/>
</template>