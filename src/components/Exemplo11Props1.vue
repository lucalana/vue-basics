<!-- 
PROPS: Propriedades
A utilização de props fornece uma comunicação entre os componentes podemos enviar informações estaticas
variaveis e funções
-->
<script setup>
import Exemplo11Props2 from './Exemplo11Props2.vue';

let cidade = 'São Paulo'
</script>
<style></style>
<template>
    <Exemplo11Props2 nome="luca" idade="24" :cidade="cidade" />
</template>