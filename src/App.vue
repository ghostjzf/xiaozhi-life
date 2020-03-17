<template>
  <el-container class>
    <el-header>
      <div id="nav">
        <router-link to="/">网站首页</router-link>|
        <router-link to="/blog">个人博客</router-link>|
        <router-link to="/resume">简历</router-link>|
        <router-link to="/about">联系方式</router-link>
      </div>
    </el-header>
    <el-main>
      <router-view />
    </el-main>
    <el-footer>
      <Footer />
    </el-footer>
  </el-container>
</template>

<script>
import Footer from "@/layout/Footer.vue";

export default {
  name: "App",
  components: {
    Footer
  }
};
</script>

<style lang="scss">
ul,
li {
  list-style: none;
  padding-left: 0;
}
.el-header {
  position: sticky;
  position: -webkit-sticky;
  top: 0px;
  border-bottom: 3px double #ececec;
  background-color: #fff;
  z-index: 10;
}
#nav {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  font-weight: 500;
}

#nav a {
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.el-header {
  line-height: 60px;
}
.el-header,
.el-footer {
  text-align: center;
  // line-height: 60px;
}

.el-main {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}
</style>
