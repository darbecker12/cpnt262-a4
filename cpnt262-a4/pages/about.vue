<template>
  <div>
  <TheNav />
  <div class="m-8 page">
    <h2 class="text-white">About</h2>
    <TheDev />
    <TheList />
  </div>
  <TheFooter />
  </div>
</template>

<script setup>

</script>

<style scoped>
.page {
  min-height: 80vh;
}
  h2 {
    margin-bottom: 20px;
    font-size: 36px;
  }
  p {
    margin: 20px 0;
  }
</style>