<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="slidebar"></router-view>
      <router-view name="main"></router-view>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header";
import PostList from "./components/PostList";
export default {
  name: "App",
  components: {
    Header,
    PostList
  }
};
</script>

<style>
body{
  background-color: #e1e1e1;
}
.main{
  max-width: 1400px;
  margin: 0 auto;
}
</style>

