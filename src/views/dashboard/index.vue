<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      涛少博客管理系统
    </div>
    <div>
      欢迎关注涛少的GitHub账号：<a href="https://github.com/taoshaolo/">https://github.com/taoshaolo/</a>   涛少咯
    </div>
    <div>
      项目资料获取：GitHub
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
