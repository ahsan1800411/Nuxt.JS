<template>
  <div>
    <h1>This is the product Details Page</h1>
  </div>
  <div>
    <slot />
  </div>
  <div>
    <footer>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </footer>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
