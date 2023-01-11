<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <h1 class="green">页面传递数据{{ msg }}</h1>
</template>

<style scoped>

</style>