<template>
  <div class="h-[1000px]"><el-calendar v-model="value" /></div>
</template>

<script lang="ts" setup>
import { ref } from "vue";
const value = ref(new Date());
</script>
