<template>
  <div class="contain">
    <div >
      <slot />
    </div> 
  </div>
  


</template>

<script setup>

  

</script>

<style scoped>
  .contain {
    height: 100vh;
  }
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