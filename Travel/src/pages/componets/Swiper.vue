<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide><img class="swiper-img"
                         src="https://source.qunarzz.com/site/images/wns/20190325_dujia_homepage_top_banner_4.jpg"
                         alt="">
      </swiper-slide>
      <swiper-slide><img class="swiper-img"
                         src="https://source.qunarzz.com/site/images/wns/20190328_qunar_dujia_homepage_2.jpg" alt="">
      </swiper-slide>
      <swiper-slide><img class="swiper-img"
                         src="https://source.qunarzz.com/site/images/wns/20190330_dujia_homepage_top_banner_5.jpg"
                         alt="">
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination" slot="pagination"></div>

    </swiper>
  </div>
</template>

<script>
  export default {
    name: "HomeSwiper",
    data() {
      return {
        swiperOption: {
          pagination: '.swiper-pagination',
          loop: true
        }
      }
    },
    methods: {}
  }
</script>

<style lang="stylus" scoped>

  .wrapper >>> .swiper-pagination-bullet-active
    background: #fff
  .wrapper
    overflow: hidden
    width: 100%
    height: 0
    padding-bottom: 31.25%
    background: #eee
    .swiper-img
      width: 100%

</style>
