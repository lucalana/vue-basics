<script setup>
let texto = '<p style="color: red;">Aprendendo html demais!</p>';

</script>

<template>
    <!-- Foco enviar estruturas HTML -->
    <div v-html="texto"></div>
    <div>{{ texto }}</div>
</template>