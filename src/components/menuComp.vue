<template>
  <div class="one-menu">
      <router-link to="/read" :class="this.$route.path == '/read' ? 'link-to selected' :'link-to' ">
        <i class="iconfont icon-shouye"></i>
         <div class="span-tile">首页</div>
      </router-link>
      <router-link to="/picture" :class="this.$route.path == '/picture' ? 'link-to selected' :'link-to' ">
        <i class="iconfont icon-tuwenliebiao"></i>
        <div class="span-tile">交易</div>
      </router-link>
      <router-link to="/music" :class="this.$route.path == '/music' ? 'link-to selected' :'link-to' ">
        <i class="iconfont icon-yinle"></i>
        <div class="span-tile">财务</div>
      </router-link>
      <router-link to="/about" :class="this.$route.path == '/about' ? 'link-to selected' :'link-to' ">
        <i class="iconfont icon-daohanglan-05"></i>
        <div class="span-tile">我的
        </div>
      </router-link>
  </div>
</template>
<script type="text/javascript">
  export default {
    'name' : 'menuComp',
    data:function(){
      return {msg:"this is menu"}
    }
  }
</script>
<style type="text/css">

</style>
