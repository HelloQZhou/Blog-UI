<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      博客管理系统
    </div>
    <div>
      所用技术：
      <br/>
      后端：SpringBoot、MybatisPlus、Mysql、Redis、SpringSecurity、EasyExcel、Swagger2...
    </div>
    <div>
      前端：Vue、ElementUI...
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
