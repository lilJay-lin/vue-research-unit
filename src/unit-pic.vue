<template>
  <div  :style="cssText">
    <img :class="[className]" :src="src" class="unit-pic-img"/>
  </div>
</template>
<script type="text/ecmascript-6">
  export default {
    label: '图片',
    props: {
      className: {
        type: String,
        default: ''
      },
      cssText: {
        type: String,
        default: function (index) {
          return 'z-index:' + (index === undefined ? 0 : index) + ';width:100%;'
        }
      },
      src: {
        type: String,
        default: 'static/assets/img/1.png'
      }
    }
  }
</script>
<style>
  .unit-pic-img{
    width: 100%;
  }
</style>
