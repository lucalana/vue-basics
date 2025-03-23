<script setup>
let validacao = false

</script>
<style>
.ok {
    color: green;
}

.falha {
    color: red;
}
</style>
<template>
    <div style="margin-top: 15px;">
        <p :class="validacao ? 'ok' : 'falha'">Utilizando diretiva class</p>
    </div>
</template>