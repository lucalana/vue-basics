<script setup>
let nomes = ['Jose', 'Josevaldo', 'Josevino', 'Josiclei', 'Joeberson', 'Joseclineo'];

</script>

<template>
    <ul>
        <li v-for="nome, index in nomes" :key="index">{{ nome }}</li>
    </ul>
</template>