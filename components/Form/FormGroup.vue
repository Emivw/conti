<template>
    <div class="form-group">

    </div>
</template>

<script setup>
import {defineAsyncComponent} from 'vue'
const Input  = defineAsyncComponent(()=> import('./Input.vue'))
const Label  = defineAsyncComponent(()=> import('./Label.vue'))
</script>

<style lang="scss" scoped>

</style>