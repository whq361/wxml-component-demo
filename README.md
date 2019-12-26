## canvas drawer


基于mpvue_canvas_drawer 进行改良，具体查看原作者github:[mpvue_canvas_drawer](https://github.com/kuckboy1994/mpvue_canvas_drawer)
 效果

![login](https://github.com/whq361/wxml-component-demo/raw/master/xg.gif)


2019.12.26 更新 在原作者基础上增加了图片圆角功能,画圆形功能。后续根据实际需求改进
### circle (圆形)
属性 | 含义 | 默认值 | 可选值
---|---|---|---
top | 左上角距离画板顶部的距离 | | 
left | 左上角距离画板左侧的距离 | | 
width | 要画多宽 | 0 | 
height | 要画多高 | 0 | 
borderRadius | 圆角 | 0 | 
background| 颜色 | 0 | 



## 使用


- 把 `components` 中的 `canvasdrawer` 拷贝到自己项目下。
- 在使用页面注册组件
  ```json
  {
    "usingComponents": {
      "canvasdrawer": "/components/canvasdrawer/canvasdrawer"
    }
  }
  ```