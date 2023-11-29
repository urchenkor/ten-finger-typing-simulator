<script setup>
defineProps({
  barText: {
    type: String,
    required: true
  }
})
</script>

<template>
    <div>
      <h1> {{barText}}</h1>
    </div>
</template>
