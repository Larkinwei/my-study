<template>
  <div>
    Index Page  afsdjflsdj  
    <msg />
    <NuxtLink to="/about">跳转至 About 页面</NuxtLink>
  </div>
</template>
<script>
  export default {
    created() {
      console.log('created')
      console.log(util)
    },
  }
</script>