<template>
  <div class="Home">
    <div class="container">
      <h1 class="title">米修在线</h1>
      <p class="lead"> 专注于线上教育, 用心做课程, 用心做服务! </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Home',
  created () {
  },
}
</script>
<style lang="scss" scoped>
.Home {
  width: 100%;
  height: 100%;
  background: url("../assets/showcase.png") no-repeat;
  overflow: hidden;
  background-size: 100% 100%;
}
.container {
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  padding-top: 100px;
  background-color: rgba(0, 0, 0, 0.7);
  text-align: center;
  color: white;
}
.title {
  font-size: 30px;
}
.lead {
  margin-top: 50px;
  font-size: 22px;
}
</style>
