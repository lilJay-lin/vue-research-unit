<template>
  <div :style="cssText">{{text}}</div>
</template>
<script type="text/ecmascript-6">
  export default {
    label: '文本',
    props: {
      cssText: {
        type: String,
        default: function (index) {
          return 'z-index:' + (index === undefined ? 0 : index) + ';width:100%;'
        }
      },
      text: {
        type: String,
        default: '我是文本'
      }
    }
  }
</script>
