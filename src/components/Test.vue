<template>
  <div>
    {{props.test}}
  </div>
</template>

<script setup lang="ts">
  


  const props = defineProps({
    test: {
      type: String,
      default: ""
    }
  });
</script>

<style scoped>

</style>