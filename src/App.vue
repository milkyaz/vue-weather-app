<script setup>
import { computed } from "vue";

const currentDate = computed(() => new Date())

</script>

<template>
  <div><p>{{ currentDate }}</p></div>
</template>
