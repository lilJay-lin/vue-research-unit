# vue-research-unit

> h5可视化配置组件

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```

## 使用

``` bash
# 安装

npm install vue-research-unit --save

# 使用

import {components} from 'vue-research-unit'

each(components, (val, key) => {
    Vue.component(key, val)
})

```

## 组件列表

* 基础组件： 图片（unit-pic）、文本（unit-txt）
* 复杂组件： banner图（unit-banner）