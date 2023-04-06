<template>
      <v-btn :color="color" :size="size" class="no-text-transform">
        <slot></slot>
        <slot name="append"></slot>
      </v-btn>
</template>

<script setup lang="ts">
const props = defineProps({
  color: String,
  size: String,
});
</script>
<style scope>
.no-text-transform{text-transform: none;}
</style>
