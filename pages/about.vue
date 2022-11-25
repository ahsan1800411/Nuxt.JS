<template>
  <div v-for="user in users" :key="user.id">
    <h1>{{ user.name }}</h1>
    <h4>{{ user.id }}</h4>
    <h4>{{ user.email }}</h4>
  </div>
</template>

<script setup>
const { data: users } = useFetch('https://jsonplaceholder.typicode.com/users');
// metadata and SEO
useHead({
  title: 'About Page',
  link: [
    {
      rel: 'stylesheet',
      href: 'htt[]',
    },
  ],
});
</script>

<style lang="scss" scoped></style>
