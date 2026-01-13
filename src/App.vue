<script setup>
import ParentComponent from './components/ParentComponent.vue';
import ParentPart2 from './components/ParentPart2.vue';
</script>

<template>
    <h1>Working with Components</h1>
    <br />

    <h2>Part1: defineProps and defineEmit</h2>
    <div>
        <ParentComponent />
    </div>

    <br />

    <h2>Part2: defineModel</h2>
    <div>
        <ParentPart2 />
    </div>
</template>
