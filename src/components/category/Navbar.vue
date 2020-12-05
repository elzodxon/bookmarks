<template>
  <div>
    <ul>
      <li>
        <router-link to="/">All</router-link>
      </li>
      <li>
        <router-link to="/category/inspiration">Inspiration</router-link>
      </li>
      <li>
        <router-link to="/category/empty">Empty</router-link>
      </li>

    </ul>
  </div>
</template>

<script>

</script>

<style scoped>

  ul {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
  }
  ul li{
    list-style: none;
  }
</style>