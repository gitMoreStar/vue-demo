<!--
 * @Author       : 马腾飞
 * @Date         : 2020-09-16 15:43:21
 * @LastEditTime : 2020-09-17 15:44:17
 * @FilePath     : /demo/vue-domo/src/views/Home.vue
-->
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App111"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
