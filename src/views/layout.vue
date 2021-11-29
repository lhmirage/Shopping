<template>
  <!-- 顶部通栏 -->
  <app-navbar></app-navbar>
  <!-- 头部组件 -->
  <div class="main">
    <RouterView />
  </div>
  <!-- 底部组件 -->
</template>

<script>
import appNavbar from '@/components/app-navbar'
export default {
  components: { appNavbar },
  name: 'Layout'
}
</script>

<style scoped lang="less">

</style>
