<template>
  <div class="container">
    <ul>
      <li>
        <router-link to="/" style="border-bottom: 2px solid #fd4300">00. all</router-link>
      </li>
      <li>
        <router-link to="/category/inspiration">01. inspiration</router-link>
      </li>
      <li>
        <router-link to="/category/news">02. news</router-link>
      </li>
      <li>
        <router-link to="/category/community">03. community</router-link>
      </li>
      <li>
        <router-link to="/category/design-systems">04. design systems</router-link>
      </li>
      <li>
        <router-link to="/category/icons">05. icons</router-link>
      </li>
      <li>
        <router-link to="/category/illustrations">06. illustrations</router-link>
      </li>
      <li>
        <router-link to="/category/mockups">07. mockups</router-link>
      </li>
      <li>
        <router-link to="/category/colors">08. colors</router-link>
      </li>
      <li>
        <router-link to="/category/motivation">09. motivation</router-link>
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
