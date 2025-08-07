<template>
  <div>
    This is Protected Dashboard
  </div>
</template>

<script setup>
definePageMeta({
  middleware: 'auth'
})
</script>