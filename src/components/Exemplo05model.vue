<script setup>
import { ref } from 'vue';

let texto = ref('');

</script>

<template>
    <div style="margin-top: 15px;">
        <input type="text" name="texto" id="texto" v-model="texto">
        <p>{{ texto }}</p>
    </div>
</template>