<script setup>
import BaseButton from './components/BaseButton.vue';


</script>

<template>
  <main class="main">
    <BaseButton>
      <template #icon>
        +
      </template>
      Сохранить
    </BaseButton>
  </main>
</template>
<style scoped>
.main {
  border-radius: 25px;
  background: var(--color-bg-main);
  padding: 60px 50px;
}
</style>
