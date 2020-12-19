---
title: Glassmorphism
date: 2020-12-20 02:43:05
author: Kinhung
tags: 杂谈
categories: 经验分享
top_img: ./img/5.jpg
cover: ./img/5.jpg
copyright_author_href: https://billisa.github.io/
copyright_url: https://billisa.github.io/2020/12/15/1/
---

# 两行代码实现毛玻璃特效

## 主要使用了Css的一个新属性

> backdrop-filter　

可以让你为一个元素后面区域添加图形效果（如模糊或颜色偏移）。 因为它适用于元素背后的所有元素，为了看到效果，必须使元素或其背景至少部分透明。

### 在backdrop-filter里面设置

``` bash
    backdrop-filter:blur(8px);
    background-color:rgba(255,255,255,0.25);
```
</n>
</n>

## 网上也有一个实用小工具，毛玻璃生成器

> [Glassmorphism CSS Generator](https://glassmorphism.com)


## 灵感转自

> https://www.bilibili.com/video/BV1GK411G7ws?t=106
