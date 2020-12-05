<template>
  <div class="home container">
    <div class="row">
      <template v-if="!loader">
        <Cards v-for="i in 10" :key="i"/>
      </template>
      <template v-else>
        yuklanmoqda...
      </template>
    </div>
  </div>
</template>

<script>

import Cards from '@/components/card/Cards'

export default {
  name: 'Home',
  components: {
      Cards
  },
  data: () => ({
    loader: false
  }),
  async created(){
    await this.fetchSites()
  },
  methods:{
    async fetchSites(){
      this.loader = true
      await this.timeout(5000)
      this.loader = false
    },
    timeout(ms) {
      return new Promise((res) => {
        setTimeout(() => {
          res()
        }, ms)
      })
    }
  }
}
</script>

<style scoped>
.row{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
