<script setup>
const props = defineProps(['message']);
const emit = defineEmits(['updateMessage']);

const emitEvent = () => {
    emit('updateMessage', 'Star Battles: Ep. IV - A New Message.');
};
</script>

<template>
    <button @click="emitEvent">Send Message</button>
    <p>{{ props.message }}</p>
</template>
