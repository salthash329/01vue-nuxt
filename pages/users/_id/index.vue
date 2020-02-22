<template>
  <section class="container">
    <h1>A Single User,ID:{{ $route.params.id}}   </h1>    
  </section>
  
</template>


<script>
export default {
  validate(data){
    // console.log(data);
    return /^\d+$/.test(data.params.id)    
  },
  layout: 'users'
  }
</script>
