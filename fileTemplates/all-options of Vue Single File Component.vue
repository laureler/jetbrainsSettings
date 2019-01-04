<template>
  <div>
    #[[$END$]]#
  </div>
</template>

<script>
export default {
  //* **************   组件的选项/数据 start **************** *//
  name: "${FILE_NAME}",
  // 组件内部数据：方法
  data () {
    return {}
  },
  // 组件传递属性：对象||数组
  props: {},
  // 计算属性：对象
  computed: {},
  // 组件方法：对象
  methods: {},
  // 组件监听器：对象
  watch: {},
  //* **************   组件的选项/数据 end **************** *//

  //* **************   组件的选项/资源 end **************** *//
  // 自定义可用组件，如果你要用组件，且组件没有全局引入，就需要import进入后，再声明出来。
  components: {},
  // 自定义指令
  directives: {},
  // 自定义过滤器
  filters: {},
  //* **************   组件的选项/资源 end **************** *//

  //* **************   组件的选项/生命周期钩子 start **************** *//
  // 应用实例 初始化之后 在数据观测和event/watcher之前调用
  beforeCreate () {
  },
  created () {
  },
  beforeMount () {
  },
  mounted () {
  },
  beforeRouteUpdate () {
  },
  updated () {
  },
  activated () {
  },
  deactivated () {
  },
  becomponentsforeDestroy () {
  },
  destroyed () {
  },
  errorCaptured (err, vm, info) {
  }
  //* **************   组件的选项/生命周期钩子 end **************** *//
}
</script>

<style scoped>

</style>
