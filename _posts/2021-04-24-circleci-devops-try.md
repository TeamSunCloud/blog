---
layout: post
title: "CircleCI 试用记录"
subtitle: ""
author: "yangchw"
header-img: "assets/img/home-bg.png"
header-mask: 0.5
tags:
  - DevOps
  - CircleCI
---

## CircleCI 试用记录

目前市面上的 CI/CD 工具比较多，但要满足企业自身使用场景还需要自己去搭建和探索，本篇文章是我在使用 [CircleCI](https://circleci.com/) 的一个记录，为公司集成和完善CI工具时多一种选择。
公司在使用开源软件如Jenkins和Tekton时，在一般场景下并没有什么问题，但如果多个部门多个开发人员同时提交并构建时，经常出现构建节点卡死的现象，也许这跟我们的构建节点服务器有关系。我想对于大部分公司来说，最终DevOps等工具可能不会再由自身去搭建，而是选择第三方服务，按使用量进行付费来解决。专业的人做专业的时，精细化的分工是不变的趋势。

