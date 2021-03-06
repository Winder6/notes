---
layout: post
title:  "前端的职业危机感"
date:   2017-12-17
tags: [ learn]
commentIssueId: 69
---

前端的职业危机感? 前端不是挺火的吗? 有危机?
* 端的危机感
* 前端的危机感
* 后端的危机感



## 端的危机感

Android 和 iOS ? 两个端 ? IoT 时代, 还会只有这两个端吗? 前端 = 渲染引擎 + web 标准, 以后还会有端的概念吗? 如果是统一, 该由谁来统一? 

如果是之前, 3 端各开发一套 app, 成本显然过高了. 类 Weex, RN 的跨端方案, 端的工作其实有点尴尬了. 要是采用 Google 推的 PWA 方案呢? 如果 Weex 继续做下去, 会不会成为一个 `类游览器` 呢? 那为什么不用 PWA 这套方案呢?性能还是主要瓶颈吗?

## 前端的危机感

* Sketch to Code, 将 UED 的视觉稿直接转成前端代码, 需要做可能只是数据绑定, 前端的意义又会变成什么?
* 当组件在行业层面上进行沉淀后, 所做的仅仅是拖动组件, 前端人才市场还需要这么大吗?
* 更自然的交互方式, 未来的交互方式, 一定是语音, 手势, 甚至是 Musk 提的人脑接口, UI 还会是重点吗?
* 类似天猫精灵的无屏设备, 我们还能做什么? 展示什么?

以后, 正如 运维行业 在阿里云的冲击下, 市场需求变小一样, 我们前端行业, 会不会以行业组件沉淀的方式, 市场需求也会变小呢? 包括以上说的几点, 或许也是不久的将来.



## 后端的危机感

Severless 方案通过  FaaS 落地, 之前的 LearnCloud 已经有类似的尝试,  AWS 的 BigTable, Lambda, 小应用已经能实现真正的 Serverless 了.

包括目前的各种 SDK, 能不能用各种 API as a Service 来替代, 业务只是需要结合各种三方 APIs 呢? 比如, 自己闲来无聊搞个人脸开门服务, 是不是可以这样:

>  三方摄像头 + IoT 三方 -> 图片获取和上传 (FaaS) -> 三方人脸识别 -> 三方身份证绑定 -> 三方登录 -> 下发指令 (FaaS) + BigTable -> 三方开锁 (物联协议)

后端需要做的事, 可能比想象的少.