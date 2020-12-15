<template>
  <div class="container">
    <VueSlickCarousel :arrows="false" :dots="false" v-bind="settings">
      <div class="mr">00. all</div>
      <div class="mr">01. inspiration</div>
      <div class="mr">02. news</div>
      <div class="mr">03. community</div>
      <div class="mr">04. design systems</div>
      <div class="mr">05. icons</div>
      <div class="mr">06. mockups</div>
      <div class="mr">08. colors</div>
      <div class="mr">09. motivation</div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'MyComponent',
  components: { VueSlickCarousel },
  data() {
    return {
      settings: {
        "arrows":false,
        "infinite": true,
        "initialSlide": 4,
        "autoplay": true,
        "autoplaySpeed": 2000,
        "speed": 500,
        "centerMode": true,
        // "centerPadding": "20px",
        "focusOnSelect": true,
        "slidesToShow": 8,
        "variableWidth": true,
        "responsive":[
          {
            "breakpoint": 1220,
            "settings":{
              "slidesToShow": 4,
              "infinite": true,
              "initialSlide": 3,
              "speed": 1000,
              "centerMode": true,
              "centerPadding": "20px",
              "focusOnSelect": true,
            }
          },
          {
            "breakpoint": 1020,
            "settings":{
              "slidesToShow": 3,
              "infinite": true,
              "initialSlide": 1,
              "speed": 1000,
              "centerMode": true,
              "centerPadding": "20px",
              "focusOnSelect": true,
            }
          },
          {
            "breakpoint": 950,
            "settings":{
              "slidesToShow": 2,
              "infinite": true,
              "initialSlide": 1,
              "speed": 1000,
              "centerMode": true,
              "centerPadding": "20px",
              "focusOnSelect": true,
            }
          },
          {
            "breakpoint": 550,
            "settings":{
              "slidesToShow": 1,
              "infinite": true,
              "initialSlide": 1,
              "speed": 1000,
              "centerMode": true,
              "centerPadding": "20px",
              "focusOnSelect": true,
            }
          },
        ]
      },
    }
  },
}
</script>

<!--<template>-->
<!--  <div class="container">-->
<!--&lt;!&ndash;    <ul>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/" style="border-bottom: 2px solid #fd4300">00. all</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/inspiration">01. inspiration</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/news">02. news</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/community">03. community</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/design-systems">04. design systems</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/icons">05. icons</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/illustrations">06. illustrations</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/mockups">07. mockups</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/colors">08. colors</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;      <li>&ndash;&gt;-->
<!--&lt;!&ndash;        <router-link to="/category/motivation">09. motivation</router-link>&ndash;&gt;-->
<!--&lt;!&ndash;      </li>&ndash;&gt;-->
<!--&lt;!&ndash;    </ul>&ndash;&gt;-->

<!--    -->
<!--  </div>-->
<!--</template>-->

<!--<script>-->

<!--</script>-->

<style scoped>
  .mr{
    margin-right: 40px;
  }
</style>
