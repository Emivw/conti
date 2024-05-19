<template>
    <div>
    <button class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" @click="toggleModal">open</button>
        <BaseModal :modalActive="modalActive" @close-modal='toggleModal'>
        <h3>this is a feature modal</h3>
        </BaseModal>
    </div>
    </template>
    
    <script setup>
    import { ref } from "vue";
    const modalActive = ref(null);
    const toggleModal = () =>{
        modalActive.value = !modalActive.value;
    }
    </script>
    
    <style>
    </style>