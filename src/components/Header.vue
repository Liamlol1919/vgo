<script setup>
defineProps({
    msg: {
        type: String,
        required: true
    }
})
</script>

<template>
    <div class="header">
        <h1>Start</h1>
    </div>
</template>
  
<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 1rem;
    padding-right: 1rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    background-color: #333;
    color: white;
}

h1 {
    font-weight: 500;
    font-size: 1.5rem;
}
</style>
  