<!--
 * @Author: your name
 * @Date: 2020-06-12 11:20:33
 * @LastEditTime: 2020-06-12 11:31:11
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \mi\src\components\demo\HelloWorld.vue
-->
<template>
  <div class="containner">
    <h3>{{msg}}</h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Hello world"
    };
  }
};
</script>
<style scoped>
.containner {
  font-size: 18px;
}
</style>
