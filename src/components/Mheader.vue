<template>
  <div>
    <div class="biaoqi_top" id="webtop">
      <h2 id="logo">导读-最新回复</h2>
    </div>
    <div class="header_btn_right">
      <a href="forum.php?mod=misc&amp;action=nav&amp;mobile=2">
        <i class="header_tool_icon"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
    import 'sass-loader' from 'sass-loader';
  data: function() {
    return {
      hTitle: ["导读-最新回复", "丽居民宿论坛", "丽居民宿论坛", "搜索", "登录"],
      tab: 0
    };
  }
};
</script>

<style lang="scss" scoped>
.biaoqi_top {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  z-index: 4;
  height: 50px;
  background-color: #3d3d3d;
  color: #fff;
  font-size: 12px;
  font-weight: normal;
  line-height: 50px;
}
.header_btn_right {
  position: fixed;
  right: 10px;
  width: 25px;
  height: 25px;
  top: 12px;
  z-index: 5;
  a {
    width: 25px;
    height: 25px;
    display: block;
  }
  i.header_tool_icon {
    background-position: 0 -41px;
  }

  i {
    background-size: 25px 110px;
    background-image: url(../../public/img/header_icon.png);
    background-repeat: no-repeat;
    display: inline-block;
    width: 25px;
    height: 25px;
  }
}
</style>