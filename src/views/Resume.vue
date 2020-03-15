<template>
  <div>
    <section>
      <ResumeItem title="基本信息">
        <el-row type="flex" class="row-bg" justify="space-between">
          <el-col :span="8"
            ><div class="grid-content bg-purple">姓名: 蒋智烽</div></el-col
          >
          <el-col :span="8"
            ><div class="grid-content bg-purple">性别: 男</div></el-col
          >

          <el-col :span="8"
            ><div class="grid-content bg-purple">年龄: 27</div></el-col
          >
        </el-row>
        <el-row class="row-bg">
          <el-col :span="8" :xs="24" :sm="24" :md="12" :lg="8"
            ><div class="grid-content bg-purple">电话: 18610270284</div></el-col
          >
          <el-col :span="8" :xs="24" :sm="24" :md="12" :lg="8"
            ><div class="grid-content bg-purple">
              邮箱: jiangzhifeng666@163.com
            </div></el-col
          >
        </el-row>
      </ResumeItem>
      <ResumeItem title="个人技能" />
      <ResumeItem title="教育" />
      <ResumeItem title="个人评价" />
    </section>
  </div>
</template>

<script>
import ResumeItem from "@/components/ResumeItem.vue";

export default {
  name: "resume",
  components: {
    ResumeItem
  }
};
</script>

<style lang="sass" scoped></style>
