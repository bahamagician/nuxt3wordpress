<template>
  <div>
    This is the about us page bwoy
     <div>{{ data }}</div>
  </div>
</template>

<script setup>
  const { data } = await useFetch('/api/hello');
  console.log(data);
</script>