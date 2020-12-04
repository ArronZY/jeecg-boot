<!--<template>-->
  <!--<div class="logo">-->
    <!--<router-link :to="{name:'dashboard'}">-->

      <!--&lt;!&ndash; update-begin- author:sunjianlei -&#45;&#45; date:20190814 -&#45;&#45; for: logo颜色根据主题颜色变化 &ndash;&gt;-->
      <!--<img v-if="navTheme === 'dark'" src="~@/assets/logo-white.png" alt="logo">-->
      <!--<img v-else src="~@/assets/logo.svg" alt="logo">-->
      <!--&lt;!&ndash; update-begin- author:sunjianlei -&#45;&#45; date:20190814 -&#45;&#45; for: logo颜色根据主题颜色变化 &ndash;&gt;-->

      <!--<h1 v-if="showTitle">{{ title }}</h1>-->
    <!--</router-link>-->
  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--import { mixin } from '@/utils/mixin.js'-->

  <!--export default {-->
    <!--name: 'Logo',-->
    <!--mixins: [mixin],-->
    <!--props: {-->
      <!--title: {-->
        <!--type: String,-->
        <!--default: 'Jeecg-Boot Pro',-->
        <!--required: false-->
      <!--},-->
      <!--showTitle: {-->
        <!--type: Boolean,-->
        <!--default: true,-->
        <!--required: false-->
      <!--}-->
    <!--}-->
  <!--}-->
<!--</script>-->
<!--<style lang="less" scoped>-->
  <!--/*缩小首页布 局顶部的高度*/-->
  <!--@height: 59px;-->

  <!--.sider {-->
    <!--box-shadow: none !important;-->
    <!--.logo {-->
      <!--height: @height !important;-->
      <!--line-height: @height !important;-->
      <!--box-shadow: none !important;-->
      <!--transition: background 300ms;-->

      <!--a {-->
        <!--color: white;-->
        <!--&:hover {-->
          <!--color: rgba(255, 255, 255, 0.8);-->
        <!--}-->
      <!--}-->
    <!--}-->

    <!--&.light .logo {-->
      <!--background-color: @primary-color;-->
    <!--}-->
  <!--}-->
<!--</style>-->