<template>
  <div class="mainApp">
    <div class="topBar">
      <span class="icon"> <i class="bi bi-app" /></span>
      <h3 class="title">Xin chào</h3>
    </div>
  </div>
</template>
<style scoped>
.mainApp {
  background: #ccc;
  width: 100%;
  height: 100%;
}
.topBar {
  height: 40px;
  width: 100%;
  background: #111;
  display: flex;
  flex-direction: row;
}
.topBar .title {
  -webkit-app-region: drag;
  padding: 3px 10px;
  color: #fff;
  line-height: 1.4;
  flex: auto;
  font-weight: 600;
}
.topBar .icon {
  text-align: center;
  width: 35px;
  padding: 5px;
  background: #ccc;
}
</style>
