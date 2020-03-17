<template>
  <ul class="list-wrap">
    <li class="list-item" v-for="(item, index) in list" :key="index">
      <span>{{ item.label }}</span>
      <el-button type="text" class="button">查看</el-button>
    </li>
  </ul>
</template>

<script>
export default {
  name: "blog",
  data() {
    return {
      list: [
        {
          label: "Css"
        },
        {
          label: "Css3"
        },
        {
          label: "Javascript"
        },
        {
          label: "Es6+"
        },
        {
          label: "安全"
        },
        {
          label: "typescript"
        },
        {
          label: "React"
        },
        {
          label: "Vue"
        },
        {
          label: "node"
        },
        {
          label: "Eggjs"
        },
        {
          label: "Express"
        },
        {
          label: "Koa"
        },
        {
          label: "Linux"
        },
        {
          label: "Nginx"
        },
        {
          label: "Docker"
        },
        {
          label: "Git"
        },
        {
          label: "Webpack"
        },
        {
          label: "Rollup"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
.list-wrap {
}
.list-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #ececec;
  margin-bottom: 5px;
  padding: 5px 0;
}
.clearfix:before,
.clearfix:after {
  display: table;
  content: "";
}

.clearfix:after {
  clear: both;
}
</style>
