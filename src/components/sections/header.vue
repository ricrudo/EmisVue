<script setup>
  import MainHeader from '@/components/sections/mainHeader.vue'
  import FxdHeader from '@/components/sections/fxdHeader.vue'
  import PostHeader from '@/components/sections/postHeader.vue'
</script>

<template>
  <div class="top-wrap">

    <!--Header-->
    <header class="header-wrap logo-left home-header overlay" role="banner">

      <!--mainHeader-->
      <MainHeader/>
      <FxdHeader/>
      <PostHeader/>
    </header>
  </div>
</template>

<style scoped>
</style>

