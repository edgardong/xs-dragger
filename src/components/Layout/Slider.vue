<template>
  <div class="xs-slider">
    <a-tabs  default-active-key="1" tab-position="left">
      <a-tab-pane key="1">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="form" />
          <div>基础组件</div>
        </div>
        Content of Tab 1
      </a-tab-pane>

      <a-tab-pane key="2">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="play-circle" />
          <div>媒体组件</div>
        </div>
        Content of Tab 2</a-tab-pane>

      <a-tab-pane key="3">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="pie-chart" />
          <div>图表组件</div>
        </div>
        Content of Tab 3</a-tab-pane>

      <a-tab-pane key="4">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="shopping" />
          <div>商品组件</div>
        </div>
        Content of Tab 3</a-tab-pane>

        <a-tab-pane key="5">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="ellipsis" />
          <div>其他组件</div>
        </div>
        Content of Tab 3</a-tab-pane>

      <a-tab-pane key="6">
        <div slot="tab" class="center-text">
          <a-icon style="font-size:22px;" type="user" />
          <div>我的页面</div>
        </div>
        Content of Tab 3</a-tab-pane>
    </a-tabs>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  computed: {},
  mounted() {},
  methods: {},
};
</script>
<style lang="less" scoped>
.xs-slider {
  padding-top: 100px;
  background: #fff;
  .light {
    background-color: transparent;
  }
  .center-text {
    text-align: center;
    .anticon {
      margin-right: 0;
    }
  }
}
</style>
