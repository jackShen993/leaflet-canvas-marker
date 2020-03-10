# leaflet-canvas-marker
~ 基于leaflet构建的 使用canvas绘制marker的 leaflet插件

## 版权
+ 基于 Leaflet.Canvas-Markers
+ 原始地址 https://github.com/eJuke/Leaflet.Canvas-Markers

## 说明

### 依赖于leaflet
在使用之前务必先引入leaflet

### 修复一些原有插件bug
+ 清空marker后报错的bug
+ 移除图层后报错的bug， 事件未清除

### 新增一些功能
+ 适配bringtoback
+ 适配bringtotop
+ 可以配置z-index

### 待新增功能
+ 隐藏和显示图层

### 可能存在的问题
+ 多个canvaslayer 事件触发时，会一起触发，所以建议只在一个layer上注册事件