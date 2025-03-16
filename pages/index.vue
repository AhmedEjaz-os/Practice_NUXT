<script setup>
// const { data: page } = await useAsyncData('content', () => queryContent('/').findOne())
const page = {
    title: 'Vue 3 APP',
    description: 'Vue 3 Description'
}
</script>

<template>
  <div>
    <h1>{{ page.title }}</h1>
    <p>{{ page.description }}</p>
    <ContentDoc />
  </div>
</template>