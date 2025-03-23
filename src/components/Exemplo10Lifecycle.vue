<!-- 
Lifecycle: são ações que acontecem em tres etapas do componente
    Antes da criação
    Durante a criação 
    Após a criação
-->
<script setup>
import { onMounted, ref } from 'vue';
let texto = ref('Texto sexo');

// Lifecycle onMounted
onMounted(() => {
    setTimeout(() => {
        texto.value = 'Vamo'
    }, 3000)
})
</script>
<style></style>
<template>
    <h1>{{ texto }}</h1>
</template>