<template>
  <div class="header">
    <div class="rapper">
      <router-link :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt />
      </router-link>
      <ul>
        <li>
          <a href="#">首页</a>
        </li>
        <li>
          <a href="#">新手入门</a>
        </li>
        <li>
          <a href="#">API</a>
        </li>
        <li>
          <a href="#">关于</a>
        </li>
        <li>
          <a href="#">注册</a>
        </li>
        <li>
          <a href="#">登录</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  background-color: rgb(68, 68, 68);
  height: 50px;
}
.rapper{
  max-width: 1400px; 
  margin: 0 auto;
}
img {
  max-width: 120px;
  margin-top: 10px;
}
ul {
  list-style: none;
  float: right;
  margin: 4px;
}
li {
  display: inline-block;
  padding: 10px 15px;
}
a {
  text-decoration: none;
  color: #ccc;
  font-size: 14px;
  text-shadow: none;
}
</style>
