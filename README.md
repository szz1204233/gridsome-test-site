# 班级门户 舒老师创新实践

## 目录
* 简介
* 网站功能
* 整体架构与使用说明
* 技术使用与特性分析
* 参考文档及开源仓库
* 开发人员

---

## 简介

舒老师创新实践班级门户是杭州电子科技大学舒亚非老师创新实践班的班级门户网站，主要用于展示项目小组的进度、成果和文档。

技术上采用gridsome框架，使用vue.js编写，使用GQL数据库语言，并借助其他博客网站作为文档存储点等，本网站只提供展示功能。

[网站首页]()

---

## 网站功能

班级门户用于展示舒亚非创新实践班级的班级详细信息
* **班级信息**：教师简介、班级详情等
* **小组信息**：班级的学员选择项目并加入对应的小组，班级门户支持查看每一个小组（包括已经结束的项目）的信息
    * 成员信息：展示小组的成员，包括已经结束课程的同学
    * 小组任务：展示小组的进度，以及每个成员的任务和完成情况
    * 疑问解答：通过采用组件来显示成员们提出的疑难杂症，并可以进行解答（***此处未定***）
    * 文档浏览：可以浏览此小组所有成员的文档和小组公有的文档
    * 成果展示：通过文档、PPT、跳转外部链接的方式来展示一个小组的成果
* **学员信息**：可以显示班级所有成员的个人信息以及他们的文档和提出过的问题以及解答（***此处未定***）
* **文档信息**：可以查看班级所有的文档，包括学员的、结课同学的、公有的。

---

## 整体架构与使用说明

### 整体架构

整个班级门户采取功能分离的设计思路，将网站的功能尽可能的简化，以达到方便使用、网站体量小的效果。
1. QQ或微信为登录机制
2. QQ群作为基于角色的组权限管理
3. 腾讯云文档作为表单输入，解决结构化数据的输入问题
4. 博客服务如csdn、公众号、思否、知乎等个人话题为主的讨论与交互
5. 借用语雀等来解决团队协同编辑等问题
6. 借用更多公共网络服务或api,如github api等
7. 自行编写Web服务解决定制的功能
8. 使用gridsome，实现自定义的内容聚合与界面定制

### 使用说明

根据整体架构的设计，班级门户的使用方法也与传统的网站不同。
1. 使用QQ或者微信或者企业微信作为登陆机制
2. 新学员通过查看小组简介或者在班级中了解每个小组
3. 个人信息通过腾讯云文档进行收集
4. 文档由学员个人选择博客平台上传，班级门户通过rss录入文档信息并显示
5. 个人博客推荐选择支持rss的平台，比如csdn、知乎专栏或者放在github.io上
6. 一些班级公开编辑文档借用语雀进行编辑

---

## 技术使用与特性分析

随开发更新！！！

---

## 参考文档及开源仓库

* [vue.js官网](https://cn.vuejs.org/)
* [vue.js菜鸟教学](https://www.runoob.com/vue2/vue-tutorial.html)
* [gridsome官网](https://www.gridsome.cn/)
* [样式提供网站](https://buefy.org/)

+ [GitHub仓库](https://github.com/szz1204233/gridsome-test-site)
+ [gitee仓库](https://gitee.com/szz1204/test-site-gitee)
+ [语雀文档](https://www.yuque.com/openxy)

---

## 开发人员

* 2017级：盛振中、靳柔怡、施泽炜
* 2018级：姚黔龙、王韬智 
