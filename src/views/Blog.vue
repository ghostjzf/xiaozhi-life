<template>
  <div>
    <el-row>
      <el-col :span="8" v-for="(item, index) in list" :key="index">
        <el-card :body-style="{ padding: '0px' }">
          <div style="padding: 14px;">
            <span>{{ item.label }}</span>
            <div class="bottom clearfix">
              <el-button type="text" class="button">操作按钮</el-button>
            </div>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
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
</style>