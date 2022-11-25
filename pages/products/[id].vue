<template>
  <div class="text-red-900 bg-red-400">Product Details about {{ id }}</div>
</template>

<script setup>
const { id } = useRoute().params;
definePageMeta({
  layout: 'products',
});
</script>

<style lang="scss" scoped></style>
