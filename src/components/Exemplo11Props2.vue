<script setup>

const props = defineProps(['nome', 'idade', 'cidade']);
</script>
<style></style>
<template>
    <h1>Nome: {{ nome }}</h1>
    <h1>Idade: {{ idade }}</h1>
    <h1>Cidade: {{ cidade }}</h1>
</template>