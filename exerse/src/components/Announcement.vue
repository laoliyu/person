<template>
  <div class="swiper">
    <swiper :options="swiperOption" class="swiper-menu">
      <!-- slides 列表项 -->
      <swiper-slide>I'm Slide 1</swiper-slide>
      <swiper-slide>I'm Slide 2</swiper-slide>
      <!-- Optional controls 控制器 -->
      <div class="swiper-scrollbar" slot="scrollbar"></div>
    </swiper>
  </div>
</template>
 
<script>
export default {
  name: 'WaimaiSwiper',
  data () {
    return {
      swiperOption: {
        loop: true// 是否循环轮播
      }
    }
  }
}
</script>
 
<style lang="stylus" scoped>
 
</style>
