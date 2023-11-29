<script setup>
defineProps({
  keyText: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <div>
      {{ keyText }}
    </div>
  </div>
</template>

<style scoped>

</style>