<template>
  <div>
    <h1>欢迎来到acongm的列表页面</h1>
    <ListItem></ListItem>
  </div>
</template>

<script lang="ts" setup>
const { data, pending, error, refresh } = useAsyncData('mountains', () =>
  $fetch('https://api.nuxtjs.dev/mountains'),
);
</script>
