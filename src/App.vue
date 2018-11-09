<template>
  <div id="app">
    <div class="header">
      <v-header></v-header>
    </div>
    <div class="tab" >
      <div class="tab-item">
        <router-link to="/goods" > 商品 </router-link>
      </div>
      <div class="tab-item">
        <router-link to="/critical" > 评论 </router-link></div>
      <div class="tab-item">
        <router-link to="/boss" > 商家 </router-link></div>
    </div>
    <div class="content">
      content
    </div>
  </div>
</template>

<script>
import header from './components/header/header'
export default {
  components: {
    'v-header': header
  }
}
</script>

<style scoped="">
  .tab {
    display: flex;
    width: 100%;
    height: 40px;
    line-height: 40;
    border: 10px solid #6aee56;
  }

  .tab .tab-item {
    flex: 1;
    text-align: center;
    background: red;
  }
</style>
