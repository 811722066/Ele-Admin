<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>
<script>
export default {
  name: 'app'
}
</script>
<style lang="less">
/*全局样式*/

body,
p,
h1,
h2 {
  padding: 0;
  margin: 0;
}

h1,
h2 {
  font-size: 14px;
  font-weight: normal;
}

body,
html {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.overflow {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.top {
  padding-top: 20px;
  padding-left: 20px;
  background: #EFF2F7;
}

.table {
  width: 100%;
  .page {
    padding: 10px;
    text-align: center;
  }
}
</style>
<style lang="less" scoped>
/*组件样式*/

#app {
  height: 100%;
  width: 100%;
}
</style>
