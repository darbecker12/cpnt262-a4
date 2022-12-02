<template>
  <div class="border-2 border-black">
    <p class="text-white">{{ product.title }}</p>
    <p class="text-white">{{ product.price }}</p>
    <p class="text-white">{{ product.id }}</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params
  const uri = 'https://fakestoreapi.com/products/' + id

  // Fetch the product

  const { data: product} = await useFetch(uri, { key: id })

  definePageMeta({
    layout: 'products'
  })
</script>

<style scoped>

</style>