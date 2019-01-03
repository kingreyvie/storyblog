<template>
  <div>
    <TheHeader />
    <main class="main-content">
      <nuxt/>
    </main>
    
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto+Mono');
* {
  box-sizing: border-box;
}

body{
  font-family: "Roboto Mono";
}

.main-content{
  margin-top: 3.5rem;
}
</style>

<script>
import TheHeader from '@/components/TheHeader/TheHeader'

export default {
  components:{
    TheHeader
  }  
}
</script>
