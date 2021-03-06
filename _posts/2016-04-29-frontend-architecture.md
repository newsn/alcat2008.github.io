---
layout: post
title: 前端架构
date: '2016-04-29 15:37:01 +0800'
tags: [architecture]
categories: architecture
---

# 前端架构（Frontend Architecture）

在大型软件中，组件化是一种共识，它一方面提高了开发效率，另一方面降低了维护成本。但是在Web前端这个领域，并没有很通用的组件模式，因为缺少一个大家都能认同的实现方式，所以很多框架/库都实现了自己的组件化方式。

架构的本质是什么？其实也是一种管理。通常我们所说的管理，都是指对于任务和人员的管理，而架构管的是机器和代码。比如说，机器的部署属于运维的物理架构，SOA属于服务架构，那么，前端的架构指什么呢？ 前端领域中，存在三种共识，第一种定义是前端组件与组件间的交互共同构成了前端架构的主题。而另一种定义中，前端架构是指将前端研发领域中各种分散的技术元素集中在一起，并对常见的前端开发问题、不足、缺陷和需求，所提出的一种解决问题的方案。还有一种说法，前端架构大部分工作要解决的是如何用工具连接框架和规范的问题。这是一个工程问题，解决的是规范与框架的链接问题，而不是简单的前端源码构建。

以上定义都反映出当前前端领域所面临的几个问题，即：模块化、组件化、工程化。

**架构的衍化** 所有代码都可控的意义非常重要。

道 => 术

架构无所谓好坏，重要的是合不合适。

--------------------------------------------------------------------------------

## 工程化

项目的组织能力

`目录结构`、`构建工具`、`编码规范`、`代码审查`
