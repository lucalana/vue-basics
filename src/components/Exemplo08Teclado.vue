<script setup>

function mensagem() {
    alert('Trabalhando com eventos de teclado!')
}
</script>
<style></style>
<template>
    <div style="margin-top: 15px;">

        <input type="text" @keypress.enter="mensagem">
    </div>
</template>