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
      <ResumeItem title="个人技能">
        <ul>
          <li>熟练使用html、css、javascript、es6</li>
          <li>熟练使用react、mobx、antd</li>
          <li>熟练使用vue、vuex、element-ui</li>
          <li>熟练使用node、eggjs、express、koa</li>
          <li>熟练使用webpack、rollup打包工具</li>
          <li>熟练使用docker</li>
          <li>熟悉docker + gitlab-runner自动化部署环境的搭建</li>
          <li>熟练使用git</li>
        </ul>
      </ResumeItem>
      <ResumeItem title="工作经历">
        <div>
          <div>北京向上一心科技有限公司(老虎证券) 2018.7 - 至今</div>
          <div>北京趣拿软件科技有限公司(去哪儿网) 2017.5 - 2018.7</div>
          <div>北京无限印象网络科技有限公司(微代驾) 2016.5 - 2017.5</div>
        </div>
      </ResumeItem>
      <ResumeItem title="项目介绍">
        <div>
          <div>Bos2.0</div>
          <div>虎友会, 快点Plus, 快点Boos</div>
          <div>易行泊车</div>
          <div>奔跑的coder(个人网站)</div>
        </div>
      </ResumeItem>
      <ResumeItem title="学历教育">
        <div>
          辽宁科技大学 2012-2016
        </div>
      </ResumeItem>
      <ResumeItem title="个人评价">
        <ul>
          <li>热衷于技术的追求，有一颗成为大牛的心</li>
          <li>性格较开朗，热爱交朋友</li>
        </ul>
      </ResumeItem>
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
