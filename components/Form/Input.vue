<template>
    <input v-bind="$attrs"
    class="input"
    @input="$emit('update:modalValue', $event.target.value)">

    </input>
</template>

<script setup>
defineProps({
    modalValue: String,
})
const emit = defineEmits(["update:modalValue"])
</script>

<style  scoped>

</style>