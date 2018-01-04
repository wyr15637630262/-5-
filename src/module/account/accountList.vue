<!--
  - accountList Vue 文件
  - @JsName accountList
  - @Description
  - @DateTime 2018/1/4 17:33
  - @author 亚茹
  -->
<template>
  <div>
    <m-Breadcrumb mTitle1="账号管理" mTitle2="账号列表"></m-Breadcrumb>
    <div class="accountList_content">

    </div>
  </div>
</template>

<script>
  import mBreadcrumb from './../../component/headerTag.vue'
  export default {
    name: 'accountList',
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
<!-- 引入 accountList Scss 文件  -->
<style lang="scss" scoped>@import "scss/accountList";</style>
