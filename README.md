# drag-image-preview 介绍

该组件是基于element-ui image 组件里的查看大图组件修改的，在基础上增加了图片可以在窗口上拖动，初始化时并不是全屏显示图片，设定了图片初始的宽为400，高度自适应。
放大、缩小、pre、next、旋转功能都有，全屏功能暂时去除了。不过通过苏表滚动可以无限放大图片，也满足全屏的需求。

使用场景：管理员需要查看身份证是否与输入的一致，需要对照做对比。

## 使用到的插件
element-ui 以及样式，如果未安装会自动安装element-ui插件，样式已经在插件里面引用了

## 用法

安装：npm i drag-image-preview 

引用：<drag-unage-preview :urlList="urlList" v-show="imgshow" @onClose="imgshow = false"></drag-unage-preview>

参数：urlList --- Array,图片地址
     onClose ---- 关闭图片事件

## github地址 https://github.com/lai-hub/drag-image-preview/
