<template>
  <div >
    <Top/>
    <hr style="background-color: #C1C1C1">
    <Navbar/>


  </div>
</template>

<script>
  import Navbar from '@/components/category/Navbar'
  import Top from '@/components/header/Top'
  export default {
    components: {
      Navbar,
      Top
    }
  }
</script>

<style>

</style>