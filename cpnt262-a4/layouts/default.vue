<template>
  <div>
    <!-- <header class="shadow-sm bg-blue-300">
      <nav class="container mx-auto p-4 flex justify-center ">
        <ul class="flex gap-4">
          <li><NuxtLink to="/" class="btn text-white">Home</NuxtLink></li>
          <li><NuxtLink to="/about" class="btn text-white">About</NuxtLink></li>
          <li><NuxtLink to="/products" class="btn text-white">Products</NuxtLink></li>
        </ul>
      </nav>
    </header> -->
    <!-- output the page content -->
    <div>
      <slot />
    </div>
  </div>
</template>

<script setup>

  

</script>

<style scoped>
.router-link-exact-active {
  color: #12b488
}
  h2 {
    margin-bottom: 20px;
    font-size: 36px;
  }
  p {
    margin: 20px 0;
  }
</style>