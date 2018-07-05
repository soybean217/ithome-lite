<template>
  <div class="container">
    <div class="column_box">
      <div class="column_img"><img src="/static/assets/birthday.png"></div>
      <input placeholder="分享的美食名称：比如小笼包"></input>
      <div class="border_bottom"></div>
    </div>
    <div class="column_box">
      <div class="column_img"><img src="/static/assets/order_3.png"></div>
      <input placeholder="规格(主材)：比如猪肉50g"></input>
      <div class="border_bottom"></div>
    </div>
    <div class="column_box">
      <div class="column_img"><img src="/static/assets/coupons.png"></div>
      <input placeholder="单价(单位:元)：比如1.5" type="digit"></input>
      <div class="border_bottom"></div>
    </div>
    <div>
      <button type="primary" bindtap="primary"> primary </button>
    </div>
  </div>
</template>
<script>
import wx from 'wx'
import { mapState, mapActions } from 'vuex'
import newsItem from '@/components/news-item'

export default {
  components: {
    newsItem
  },
  computed: {
    ...mapState([
      'slides',
      'news'
    ])
  },
  mounted() {},
  onPullDownRefresh() {},
  // onReachBottom () {
  //   this.loadmore()
  // },
  methods: {

  }
}

</script>
<style lang="less" scoped>


</style>
