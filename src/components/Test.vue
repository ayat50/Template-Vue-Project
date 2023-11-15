<script setup>
defineProps({
    name: {String},
    mobile: {String},
})
</script>

<template>
    <h1> My name is {{ name }}. </h1>
    <h3> Mobile No {{ mobile }}. </h3>
</template>