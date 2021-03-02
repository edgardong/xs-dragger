<template>
  <a-config-provider :locale="zh_CN">
    <div id="app">
      <main-page></main-page>
    </div>
  </a-config-provider>
</template>

<script>
import zh_CN from 'ant-design-vue/lib/locale-provider/zh_CN'
import MainPage from './pages/main'
export default {
  name: 'app',
  data() {
    return {
      zh_CN,
    }
  },
  components: {
    MainPage
  }
}
</script>

<style>
body {
  overflow: hidden;
}
</style>
