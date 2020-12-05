<template>
  <div id="app">
    <Header/>
    <router-view/>

    <Footer/>

  </div>
</template>
<script>
  import Header from '@/components/header/Header'
  import Footer from '@/components/footer/Footer'
  export default {

    components: {
      Footer,
      Header
    }
  }
</script>
<style>

@font-face {
  font-family: 'cotham_sansregular';
  src: url('./assets/fonts/cothamsans-webfont.woff2') format('woff2'),
  url('./assets/fonts/cothamsans-webfont.woff2') format('woff');
  font-weight: normal;
  font-style: normal;

}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'cotham_sansregular', Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.container{
  max-width: 1320px;
  margin: 0 auto;
  padding: 20px;
}

ul li{
  list-style: none;
}

ul li a{
  text-decoration: none;
  color: black;
}

</style>
