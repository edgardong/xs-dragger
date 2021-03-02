<template>
  <div class="xs-main">
    <a-layout>
      <!-- 顶部导航 -->
      <a-layout-header class="header light">
        <xs-header></xs-header>
      </a-layout-header>

      <a-layout class="content">
        <!-- 左侧侧边栏 -->
        <a-layout-sider class="light">
          <xs-slider></xs-slider>
        </a-layout-sider>
        <!-- 右侧内容 -->
        <a-layout-content></a-layout-content>
      </a-layout>
      <!-- 底部部分 -->
      <a-layout-footer>
        <xs-footer></xs-footer>
      </a-layout-footer>
    </a-layout>
  </div>
</template>
<script>
import XsHeader from "@/components/Layout/Header";
import XsSlider from "@/components/Layout/Slider";
import XsFooter from "@/components/Layout/Footer";
export default {
  components: {
    XsHeader,
    XsSlider,
    XsFooter
  },
  data() {
    return {};
  },
  computed: {},
  mounted() {},
  methods: {},
};
</script>
<style lang="less" scoped>
.xs-main {
  height: 100vh;
  display: flex;
  flex-direction: column;
  .header {
    padding: 0;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 9;
  }
  .light {
    background: transparent;
  }
  .content {
    flex: 1;
  }
}
</style>
