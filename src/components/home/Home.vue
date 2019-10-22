<template>
  <div class="home">
      <home-header></home-header>
  </div>
</template>

<script type="text/ecmascript-6">
import HomeHeader from "./components/Header";
export default {
  data() {
    return {};
  },
  components: {
    HomeHeader
  }
};
</script>

<style scoped lang="stylus">
.home {
  font-size: 24px;

  .tilte {
    &.active {
    }
  }

  .content {
  }
}
</style>
