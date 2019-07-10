<template>
  <div class="app-container">
    <!--顶部-->
    <mt-header fixed title="固定在顶部"></mt-header>

    <!--中间的路由router-view区域-->


    <!--底部Tabbar区域-->
    <h1>这是 App 组件</h1>
    <!--主页面底部选项卡-->
    <nav class="mui-bar mui-bar-tab">
      <a id="defaultTab" class="mui-tab-item mui-active" href="template/head.html">
        <span class="mui-icon mui-icon-home"></span>
        <span class="mui-tab-label">首页</span>
      </a>
      <a  class="mui-tab-item" href="template/controls.html">
        <span class="mui-icon mui-icon-checkbox"></span>
        <span class="mui-tab-label">控件</span>
      </a>
      <a class="mui-tab-item" href="template/chat.html">
        <span class="mui-icon mui-icon-email"><span class="mui-badge">5</span></span>
        <span class="mui-tab-label">列表</span>
      </a>
      <a class="mui-tab-item" href="template/my.html">
        <span class="mui-icon mui-icon-person"></span>
        <span class="mui-tab-label">我的</span>
      </a>
    </nav>


  </div>
</template>
<style lang="scss" scoped="">
  .app-container{
    padding-top: 40px;
  }

</style>