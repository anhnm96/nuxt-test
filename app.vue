<template>
  <div>
    data {{ data }}
    <NuxtWelcome />
  </div>
</template>

<script setup>
const {data} = await useFetch('/api/hello')

</script>