<template>
  <div id="app">
    <div class="header">
      <v-header></v-header>
    </div>
    <div class="tab">
      tab
    </div>
    <div class="content">
      content
    </div>
  </div>
</template>

<script>
import header from './components/header/header'
// Vuew.component('head-view'{
//   header
// }),
export default {
  components: {
    'v-header': header
  }

}

</script>

<style>

</style>
