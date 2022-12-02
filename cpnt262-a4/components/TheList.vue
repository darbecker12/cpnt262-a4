<template>
  <div>
    <h1 class="text-xl text-white mt-8">What I would like to create:</h1>
    <div>
    <button class="text-white" > display list</button>
    
    <ul >
      <li class="m-2 text-white" v-for="site in websites">{{ site.site }}</li> 
    </ul>
   
  </div>
  </div>
</template>

<script> 


const websites =  [{site: 'Sports Website'}, {site: 'Photography Website'}, {site:"E-Commerce Website" }]
  


</script>

<style>

</style>