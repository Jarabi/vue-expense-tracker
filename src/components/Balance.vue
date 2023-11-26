<template>
    <h4>Your Balance</h4>
    <h1 id="balance">KSH. {{ total.toLocaleString('en-US') }}</h1>
</template>

<script setup>
import { defineProps } from 'vue';
const props = defineProps({
    total: {
        type: Number,
        required: true
    }
})
</script>