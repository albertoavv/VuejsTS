<template>
    <div>
        <button
            @click="contador++"
            class="btn btn-primary"
            >
            Contador {{ contador }}
        </button>
    </div>
</template>

<script setup lang="ts">
import {ref} from 'vue';

const contador = ref(0);

</script>

<style scoped>

</style>