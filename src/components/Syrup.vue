<template>
    <div class="Syrup" :style="{ backgroundColor: currentSyrup }"></div>
</template>

<script setup lang="ts">
import { currentSyrup } from '../stores/beverage';
import { computed } from 'vue';
</script>

<style scoped>
.Syrup {
    position: relative;
    width: 100%;
    height: 20%;
}
</style>
