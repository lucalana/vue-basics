<script setup>
let exibir = true;
let media = 6;

</script>

<template>
    <h1 v-if="exibir">Hello Word!!</h1>

    <p v-if="media >= 7">Aprovado!</p>
    <p v-else-if="media >= 5">Em exame!</p>
    <p v-else>Reprovado!</p>
</template>