<template>
  <div class="home">
    <header>
      <div class="top">
        <h1 class="c-page-title">主页</h1>
        <div class="search">
          <i class="icon icon-search"></i>
        </div>
      </div>
      <!-- swiper -->
    </header>
  谭本聪3月20号日报：
  调整小程序部分样式, 编写会员注册页的js。
    <div class="tab">
      <div class="tab-switch-group">
        <div class="tap-switch"></div>
      </div>
      <!-- group end -->
      <div class="tab-panel-group">
        <div class="tab-panel">
          <div class="product-list">
            <div class="product-item">
              <img class="product-picture" src="" alt="">
              <h2 class="product-name"></h2>
              <span class="product-price"></span>
            </div>
          </div>
          <div class="showMore"></div>
        </div>
      </div>
      <!-- group end -->
    </div>
  </div>
</template>

<script>
// Use Vuex

export default {
  data () {
    return {
      data: {
        imgUrls: [''],
        indicatorDots: false,
        autoplay: false,
        interval: 5000,
        duration: 1000
      }
    }
  },
  methods: {
    test () {
      return false
    }
  }
}
</script>

<style>
</style>
