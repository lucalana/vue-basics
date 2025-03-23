<script setup>
function validarForm(e) {
    e.preventDefault()
    alert('Formulario enviado!')
}
</script>
<style></style>
<template>
    <div style="margin-top: 10px;">
        <form action="" @submit="validarForm">
            <button>Enivar</button>
        </form>
    </div>
</template>