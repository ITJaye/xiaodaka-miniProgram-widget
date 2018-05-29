xiaodaka-miniProgram-widget
-------------------------------------

小打卡小程序挂件

为你的小程序增加打卡互动功能

在你的小程序中引入小打卡圈子的链接模板代码

目前的展现形式为右下角圆形悬浮打卡按钮
点击按钮后可唤起小打卡小程序 并跳转到你的圈子

###### 步骤：
1. 在你的公众号上申请关联小打卡小程序
小打卡app_id：wx855c5d7718f218c9
1. 登录 http://web.sharedaka.com  获取你的圈子链接
1. 在你的小程序中引入template下的文件

```
<import src="../../template/xiaodaka-btn/xiaodaka-btn.wxml"></import>

<template is="xiaodaka-btn__index" data="{{bottom: 12,right: 3,appId: 'wx855c5d7718f218c9',path: '/pages/index/index',openType: 'navigate',extra: '',txt: '打卡',version: 'release'}}"></template>
```
