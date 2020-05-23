<template>
  <div id="app">
    <!-- //导航栏 -->
    <mt-header fixed title="首页"></mt-header>

    <router-view/>

    <!-- 底部 -->
     <mt-tabbar >
       <mt-tab-item id="index">
         <img slot="icon" src="./assets/all.png">
         首页
       </mt-tab-item>
       <mt-tab-item id="map">
         <img slot="icon" src="./assets/map.png">
         地图
       </mt-tab-item>
       <mt-tab-item id="foot">
         <img slot="icon" src="./assets/foot.png">
         美食
       </mt-tab-item>
       <mt-tab-item id="string">
         <img slot="icon" src="./assets/string.png">
         设置
       </mt-tab-item>
     </mt-tabbar>


  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>


</style>
