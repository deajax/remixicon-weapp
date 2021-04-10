# 微信小程序 Remix Icon 组件

 &nbsp;

![logo](https://camo.githubusercontent.com/fe03c062b73675cd8c025eb82885a98261810bd4/687474703a2f2f63646e2e72656d697869636f6e2e636f6d2f6c6f676f2d6769746875622e737667)

 &nbsp;

## Remix Icon简介

> Remix Icon v2.5.0
>
> https://remixicon.com
>
> https://github.com/Remix-Design/RemixIcon
>
> Copyright RemixIcon.com

Remix Icon 是一套面向设计师和开发者的开源图标库。我们在设计之初将图标风格定义为中性风格，以便适用于各种用户群的项目。与拼凑混搭的图标库不同，Remix Icon 的每一枚图标都是由设计师按照统一规范精心绘制的，并确保每一枚图标在拥有完美像素对齐的基础上风格一致且简洁易读。图标以24x24网格为基准，分为“线性图标”和“面型图标”两种风格。所有的图标均可免费用于个人项目和商业项目。

![icon demo](https://camo.githubusercontent.com/3060a54ac83251b8af14cd1c9440b86c3aaf93b3/687474703a2f2f63646e2e72656d697869636f6e2e636f6d2f707265766965772e737667)

整套图标库 [remixicon.com](https://remixicon.com/).

&nbsp;

## Remix Icon For Weapp简介

在微信小程序中使用Remix Icon图标。

&nbsp;

## 使用说明

**在微信小程序中使用Remix Icon图标：**

1、下载components文件夹下的所有内容放到小程序根目录下。

2、在app.json中注册组件：

```
"usingComponents": {
    "remix-icon": "/components/remixicon v2.5.0/index",
}
```

3、在页面中使用组件：

```
<remix-icon name="ri-home-line" />
```

4、图标库

> 在[remixicon.com](https://remixicon.com/)点击您想要的图标, 在打开的图标窗口中复制class name替换name内的字段。

5、更改尺寸（默认px）

```
<remix-icon name="ri-home-line" size="24" />
```

6、更改icon的css样式

```
/* wxml */

<view class="avatar">
    <remix-icon name="ri-home-line" />
</view>
```

```
/* wxss */

.avatar .remix {
    color: red;
}
```

## 或者
**直接在app.wxss中引入：**
```
@import 'https://cdn.jsdelivr.net/gh/deajax/remixicon-weapp/dist/remixicon.wxss';
```
