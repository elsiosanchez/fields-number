<template>
  <FieldNumber :num="number" />
</template>
<script lang="ts" setup>
import { ref } from 'vue';
const number = ref(4);
</script>
