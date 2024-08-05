<template>
    <div>
        <input type="text" v-model="nombre">
        <input type="number" v-model="edad">
        <input type="date" v-model="fecha">
    </div>

    <pre>
        {{ nombre }} / {{ edad }} / {{ fecha }}
    </pre>
</template>

<script setup lang="ts">
import { ref } from "vue";

const nombre = ref('')
const edad = ref(0)
const fecha = ref('')


</script>

<style scoped>

</style>