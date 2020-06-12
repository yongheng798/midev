<!--
 * @Author: your name
 * @Date: 2020-06-12 11:20:33
 * @LastEditTime: 2020-06-12 11:52:24
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \mi\src\components\demo\HelloWorld.vue
-->
<template>
  <div class="containner">
    <h3>{{msg}}</h3>
    <div class="titile">
      <h3>local titile</h3>
    </div>
    <header>
      <h1>{{msg}}</h1>
    </header>
    <main>
      <div class="containers">
        <div class="flex">
          <div class="row">row1</div>
        </div>
      </div>
    </main>
    <footer>
      <p>copyright chenpinfu {{fullYear}}</p>
    </footer>
    <p>change on line</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Hello world",
      fullYear: "2020"
    };
  },
  methods: {
    getFullYear() {
      this.fullYear = new Date().getFullYear();
    }
  }
};
</script>
<style scoped>
.containner {
  font-size: 18px;
}
</style>
