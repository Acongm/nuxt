<template>
  <div>
    <h1>欢迎来到acongm的第一个页面 {{foo}}</h1>
    <NuxtLink to="/list">进入列表页</NuxtLink>

  </div>
</template>


<script lang="ts" setup>
const foo = useFoo();
</script>
