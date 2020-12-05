<template>
  <ul>
    <li>
        <router-link class="router-lang" to="/ru">ru</router-link>
    </li>
    <li>
      <router-link class="router-lang" to="/" style="color: black">eng</router-link>
    </li>
    <li>
      <router-link class="router-lang" to="/uz">uz</router-link>
    </li>
  </ul>
</template>

<script>

</script>

<style scoped>
  ul li{
    margin-top: 6px;
  }

  .router-lang{
    color: #C1C1C1;
  }
</style>
