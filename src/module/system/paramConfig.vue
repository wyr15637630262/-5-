<!--
  - paramConfig Vue 文件
  - @JsName paramConfig
  - @Description
  - @DateTime 2018/1/4 17:42
  - @author 亚茹
  -->
<template>
  <div>
    <m-Breadcrumb mTitle1="系统管理" mTitle2="参数配置"></m-Breadcrumb>
    <div class="paramConfig_content">

    </div>
  </div>
</template>
<script>
  import mBreadcrumb from './../../component/headerTag.vue'
  export default {
    name: 'paramConfig',
    data () {
      return {
      }
    },
    methods: {
    },
    mounted () {
    },
    components: {
      mBreadcrumb
    }
  }
</script>
<!-- 引入 paramConfig Scss 文件  -->
<style lang="scss" scoped>@import "scss/paramConfig";</style>
