<template>
  <el-time-picker v-bind="$attrs" v-on="$listeners" :style="{ width: width }">
    <slot></slot>
  </el-time-picker>
</template>

<script>
export default {
  name: 'nui-time-picker',
  props: {
    width: {
      type: String,
      default: '100%',
    },
  },
  data() {
    return {}
  },
  computed: {},
  created() {},
  mounted() {},
  methods: {},
}
</script>
<style lang="scss">
.el-date-editor .el-range-separator {
  min-width: 18px;
}
</style>
