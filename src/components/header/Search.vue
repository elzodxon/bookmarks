<template>
  <div class="search-section">
    <input class="search-input" type="search" placeholder="search" v-model="search" >
    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
      <circle cx="8" cy="8" r="7" stroke="#C1C1C1" stroke-width="2"/>
      <rect width="9.65772" height="1.97726" transform="matrix(0.715241 0.698878 -0.715241 0.698878 13.0924 11.8686)" fill="#C1C1C1"/>
    </svg>

  </div>
</template>


<script>

</script>
<style scoped>
  .search-section{
    display: flex;
    align-items: center;
  }

  .search-input{
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 16px;
    letter-spacing: 0em;
    text-align: left;
    border: none;
    outline: none;
    width: 70px;
    color: #C1C1C1;
  }
</style>