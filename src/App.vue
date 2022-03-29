<template>
  <h1>Hello World !</h1>
  <button class="btn btn-primary" @click="show = !show"></button>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const show = ref(false);
</script>

<style lang="scss">
@import './assets/scss/base.scss';
</style>
