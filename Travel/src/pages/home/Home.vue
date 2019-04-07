<template>
  <div>
    <HomeHeader></HomeHeader>
    <HomeSwiper></HomeSwiper>
    Hello word
  </div>
</template>

<script>

  import HomeHeader from '../componets/Header'
  import HomeSwiper from '../componets/Swiper'

  export default {
    components: {
      HomeHeader,
      HomeSwiper
    },
    name: "home.Home",
    data() {
      return {}
    },
    methods: {}
  }
</script>

<style scoped>

</style>
