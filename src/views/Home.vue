<template>
  <div class="app-container">
     <p>本项目是基于vue、Element、mockjs构建的（全部为当前最新版本），其中引入了高德地图、Echarts、Excel表格导出、富文本编辑器的第三方组件。</p>
	 <p>还有部分本人在实际项目中自己写的组件也在项目中有应该实例，内容还在不断更新中.....</p>
	 <a :href='Url' target="_blank">下载项目</a>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: '欢迎',
    }
  },
  methods: {

  }
}
</script>
<style scoped>
h1, h2 {
  font-weight: normal;
}

</style>
