<template>
  <div>
    <tab-bar>
      <tab-item>
        <img src="../../../assets/img/home/zhuye.svg" slot="img" />
        <div slot="text">主页</div>
      </tab-item>
      <tab-item>
        <img src="../../../assets/img/shop/shop.svg" slot="img" />
        <div slot="text">商城</div>
      </tab-item>
      <tab-item>
        <img src="../../../assets/img/cart/shopcart.svg" slot="img" />
        <div slot="text">购物车</div>
      </tab-item>
      <tab-item>
        <img src="../../../assets/img/myself/my.svg" slot="img" />
        <div slot="text">我的</div>
      </tab-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "../../common/tabbar/TabBar";
import TabItem from "../../common/tabbar/TabItem";
export default {
  name: "TabBarContent",
  components: {
    TabBar,
    TabItem,
  },
};
</script>

<style>
</style>