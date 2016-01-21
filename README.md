# [SymphonyX](https://github.com/FangStarNet/symphonyx) [![Build Status](https://img.shields.io/travis/FangStarNet/symphonyx.svg?style=flat)](https://travis-ci.org/FangStarNet/symphonyx)

## 简介

SymX 是 [Sym](https://github.com/b3log/symphony) 的企业版，实现企业内网论坛。

## 对 Sym 的改造

### 增强

#### 航海日记

航海日记相当于日报。

用户每天为段落，一天为一节，一周为一章。将每个人在公司的成长经历记录下，旨在帮助小伙伴了解公司历史以及其他小伙伴工作内容和进度。

 * 用户可配置所在开发组
 * 特殊的帖子类型：航海日记段落、航海日记节/章（节/章为底层类型，界面上不可见）
 * 每周末以管理员账号自动生成章，内容为空（留待管理员更新），在浏览时以内容+本周的所有航海日记节索引+节内容（段落内容汇总）
 * 航海日记章需要在前端做一个分组排序功能，方便按时间/人/组织架构进行展现

#### 搜索

 * 去除百度站内搜索
 * 实现新的搜索，过滤条件：
   * 关键字（标题、标签、内容）全文检索
   * 时间范围
   * 作者
   * 文章类型（文章/思绪/航海日记）

### 其他

 * 文件上传改为可配置保存到服务器本地
 * 去除同步
 * 等等（去除一些内网上不用的特性）
