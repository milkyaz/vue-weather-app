<script setup>

</script>
<template>
    <button class="cs-button">Кнопка</button>
</template>
<style scoped>
.cs-button {
    border: none;
    border-radius: 10px;
    background: var(--gradient);
    padding: 14px;
    font-family: var(--font);
    font-size: 20px;
    font-weight: 600;
    color: var(--primary);
    cursor: pointer;
}

.cs-button:hover {
    background: var(--gradient-inverted);
}
</style>