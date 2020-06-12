<template>
  <tab-bar>
      <tab-bar-item path="/home" activeClor='red'>
        <img slot="item-icon" src="~assets/img/tabbar/home.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/home-active.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeClor='red'>
        <img slot="item-icon" src="~assets/img/tabbar/fl.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/fl-active.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/shopcart" activeClor='red'>
        <img slot="item-icon" src="~assets/img/tabbar/shop.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/shop-active.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeClor='red'>
        <img slot="item-icon" src="~assets/img/tabbar/me.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/me-active.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>
<script>
import TabBar from 'components/common/tabbar/TabBar'
import TabBarItem from 'components/common/tabbar/TabBarItem'
export default {
  name: "Maintabbar",
  data () {
    return {
    };
  },
  components: {
    TabBar,
    TabBarItem
  }
}
</script>
<style>
</style>
