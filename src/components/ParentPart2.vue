<template>
    <ChildPart2 v-model="sharedMessage" />
    <p>Current Message: {{ sharedMessage }}</p>
</template>

<script setup>
import {ref} from 'vue';
import ChildPart2 from './ChildPart2.vue';

const sharedMessage = ref('');
</script>
