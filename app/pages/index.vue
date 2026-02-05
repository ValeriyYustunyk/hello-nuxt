<script setup lang="ts">
const { data } = await useFetch('/api/hello')

</script>

<template>
   Hello from {{ data?.hello }}
</template>
