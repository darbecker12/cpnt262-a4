<template>
  <div>
    <TheNav />
    <div class="grid grid-cols-4 gap-5 contain m-4">
      <div v-for="p in products" class="text-white border-2 border-black p-4 hover:bg-gray-500">
        <NuxtLink :to="`/components/${p.id}`">{{ p.title }}</NuxtLink>
      </div>
    </div>
    <TheFooter />
  </div>
</template>

<script setup>
  definePageMeta({
    layout: 'products'
  })

  // Fetch the products
  const { data: products } = await useFetch('https://fakestoreapi.com/products')
</script>

<style scoped>
  .contain {
    height: 80vh;
  }
</style>