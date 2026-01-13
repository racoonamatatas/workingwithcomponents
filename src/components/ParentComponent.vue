<script setup>
import {ref} from 'vue';
import ChildComponent from './ChildComponent.vue';

const message = ref('');

const handleMessage = newMessage => {
    message.value = newMessage;
};
</script>

<template>
    <ChildComponent :message="message" @updateMessage="handleMessage" />
</template>
