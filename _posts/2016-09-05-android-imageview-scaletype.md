---
layout: post
title: "Android ImageView ScaleType"
tagline: ""
description: "描述 Android ImageView ScaleType 使用"
category: Android
tags: [Android, AndroidDev, ]
last_updated: 
---

ImageView 的 ScaleType 属性决定了图片在 View 上显示时的样子，是比例缩放，还是显示图片的整体或者局部等等。

设置的方式有两种：

1. 在布局 Layout 中 ImageView 中定义 `android:scaleType="center"`
2. 在代码中调用 `imageView.setScaleType(ImageView.ScaleType.CENTER);`

## 8 种 ScaleType

所有的 Scale 方式有 8 种，[文档](https://developer.android.com/reference/android/widget/ImageView.ScaleType.html) 中可以查看到，下文也会详细介绍。


### ImageView.ScaleType.CENTER

按图片原大小居中显示，不缩放原图片，当原始图片长/宽超过View的长/宽，则截取图片的居中部分显示，当图片长/宽小于 View 长宽时，可能造成填充不完全。

### ImageView.ScaleType.CENTER_CROP

按比例扩大图片的size居中显示，不改变图片宽高比，使得图片长(宽)等于或大于View的长(宽)，图片填充满 ImageView，可能产生裁剪，此时能保证 View 被完整填充。

### ImageView.ScaleType.CENTER_INSIDE

将图片的内容完整居中显示，通过按比例缩小或原来的size使得图片长/宽小于或等于View的长/宽，可能产生黑边。

### ImageView.ScaleType.FIT_CENTER

把图片按比例扩大/缩小到 ImageView 的宽度，使用 CENTER 方式居中显示

`FIT_START`, `FIT_END` 在图片缩放效果上与 `FIT_CENTER` 一样，只是显示位置不同，`FIT_START` 是置于顶部，`FIT_CENTER` 居中，`FIT_END` 置于底部。


### ImageView.ScaleType.FIT_XY
不按比例缩放图片，把图片塞满整个 View ，如果 View 与 原图片长宽不对应，可能造成图片长宽比改变，以及图片变形。

### ImageView.ScaleType.MATRIX
通过变化矩阵来设置 ImageView 大小。可以通过设置 matrix 然后手动利用 matrix 来调整 ImageView 可以实现 ImageView 的双指缩放和旋转。不过似乎用的很少。

具体细节可以继续再讨论。

如果要看效果图，[这里](http://etcodehome.blogspot.hk/2011/05/android-imageview-scaletype-samples.html) 很不错，一目了然。

## ImageView src 与 background 属性区别

每一种 View 都可以包含背景图片，而 ImageView 的 src 可以设置 ScaleType ，adjustViewBounds 等属性。


## reference

- <http://stackoverflow.com/questions/5454491/what-is-the-difference-between-src-and-background-of-imageview>
- <https://guides.codepath.com/android/Working-with-the-ImageView>
- <http://etcodehome.blogspot.hk/2011/05/android-imageview-scaletype-samples.html>