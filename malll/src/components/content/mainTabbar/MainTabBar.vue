<template>
<div>
    <tab-bar>
      <tab-bar-item path="/home">
        <img slot="item-icon" src="~assets/images/tabbar/home.png" alt="" />
        <img slot="item-icon-active" src="~assets/images/tabbar/home_active.png" alt="" />
        <div slot="item-text">首页</div>
      </tab-bar-item>
       <tab-bar-item path="/category">
        <img slot="item-icon" src="~assets/images/tabbar/category.png" alt="" />
        <img slot="item-icon-active" src="~assets/images/tabbar/category_active.png" alt="" />
        <div slot="item-text">分类</div>
      </tab-bar-item>
       <tab-bar-item path="/cart">
        <img slot="item-icon" src="~assets/images/tabbar/cart.png" alt="" />
        <img slot="item-icon-active" src="~assets/images/tabbar/cart_active.png" alt="" />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
       <tab-bar-item path="/profile">
        <img slot="item-icon" src="~assets/images/tabbar/profile.png" alt="" />
        <img slot="item-icon-active" src="~assets/images/tabbar/profile_active.png" alt="" />
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
    </div>
</template>

<script>
import TabBar from "components/common/TabBar/TabBar.vue";
import TabBarItem from "components/common/TabBar/TabBarItem.vue";
export default {
components: {
    TabBar,
    TabBarItem
}
}
</script>

<style>

</style>