<template>
  <div class="container">
    <ul class="container-wrapper">
      <li>
        <ul class="container-wrapper__logo">
          <li>
            <router-link class="logo" to="/">Saved</router-link>
          </li>
          <li>
            <p>-  these are hand-made bookmarks for various services, sites, references, and more for the designer</p>
          </li>
        </ul>
      </li>

      <li>
        <ul class="container-wrapper__right">
          <li>
            <Search/>
          </li>
          <li>
            <OpenInfo/>
          </li>
          <li>
            <Lang/>
          </li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<script>
  import Search from '@/components/header/Search'
  import OpenInfo from '@/components/modal/OpenInfo'
  import Lang from '@/components/language/Lang'
  export default {
    components: {
      Search,
      OpenInfo,
      Lang
    }
  }
</script>

<style scoped>

  .container-wrapper{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .container-wrapper__logo{
    display: flex;
    justify-content: space-between;
    width: 65%;
  }

  .container-wrapper__logo p{
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 14px;
    letter-spacing: 0em;
    text-align: left;
    margin-left: 12px;
  }
  .container-wrapper__right{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .container-wrapper__right li{
    margin-right: 30px;
  }
  .logo{
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 30px;
    letter-spacing: 0em;
    text-align: left;
  }
</style>