<template>
  <div class="header">
    <div class="header-left">
      <i class="iconfont iconfanhui"></i>
    </div>
    <div class="header-input">
      <i class="iconfont iconsousuo"></i>请输入城市/景点/游玩主题
    </div>
    <div class="header-right">城市<i class="iconfont iconjiantou"></i>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data() {
    return {};
  },
  components: {}
};
</script>

<style scoped lang="stylus">
@import '~styles/varibles.styl';
.header {
  height: 40px;
  width: 100%;
  display: flex;
  color: #fff;
  font-size: 12px;
  line-height: 40px;
  text-align: center;
  background: $bgColor;

  .header-left {
    display: inline-block;
    flex: 0 0 50px;
    width: 50px;
  }

  .header-input {
    flex: 1;
    background: #fff;
    margin: 6px 0;
    border-radius: 1px;
    color: rgb(147, 153, 159);
    line-height: 28px;
    text-align: left;
    padding-left:5px;
    .iconsousuo{
        margin-right :5px;
        font-size:12px;
        }
  }

  .header-right {
    display: inline-block;
    flex: 0 0 50px;
    width: 50px;

    .iconjiantou {
      font-size: 8px;
    }
  }
}
</style>
