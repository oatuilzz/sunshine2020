<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <el-row>

    <el-button type="warning" icon="el-icon-star-off" circle></el-button><div>张语文的个人主页</div>
</el-row>
      <el-button @click="startHacking">Start</el-button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    startHacking () {
      this.$notify({
        title: '奥利给!',
        type: 'success',
        message: '点开了你就是我的人了',
        duration: 5000
      })
    }
  }
}
</script>

<style>
#app {
  font-family: Helvetica, sans-serif;
  text-align: center;
}
</style>
