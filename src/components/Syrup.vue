<template>
    <div class="Syrup" :style=" { backgroundColor: currentSyrup }"></div>
</template>

<script setup lang="ts">
import { currentSyrup } from "../stores/beverage";
import { computed } from 'vue';
</script>

<style scoped>
.baseBeverage {
    position: relative;
    width: 100%;
    height: 100%;
    bottom: 0;
    z-index: 300;
}
</style>