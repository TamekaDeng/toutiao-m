<template>
  <div id="app">
    <h1>头条新闻</h1>
    <!-- 路由的出口：被匹配到到的路由，就会渲染到这个位置 -->
    <router-view/>
  </div>
</template>
// 这个不是必须的但是建议补全
<script>
export default {
  // 组件名，作用方便在浏览器的调试工具里通过名字来搜索到这个组件
  name: 'App'
}
</script>
<style lang="less">
// 默认事例的样式
</style>
