<script setup>
import { computed } from "vue";

const currentDate = computed(() => new Date())

</script>

<template>
  <div><p style="font-family: MyCustomFont">{{ currentDate }}</p></div>
</template>
