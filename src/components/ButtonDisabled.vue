<script setup>
    const props = defineProps({
        operador: String
    })
     
    
</script>

<template>
    <button
        type="button"
        class="h-10 w-10 flex items-center justify-center font-bold bg-gray-500 
        rounded-full hover:outline-none text-white text-2xl hover:ring-2 hover:ring-offset-2 
        hover:ring-gray-500"
        disabled
        @click="$emit('fn')"
        
    >{{operador}}</button>
</template>