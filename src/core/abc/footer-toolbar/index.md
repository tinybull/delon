---
title: footer-toolbar
subtitle: 底部工具栏
order: 110
cols: 1
module: AdFooterToolbarModule
---

固定在底部的工具栏。

## 何时使用

固定在内容区域的底部，不随滚动条移动，常用于长页面的数据搜集和提交工作。

## API

参数 | 说明 | 类型 | 默认值
----|------|-----|------
ng-content | 工具栏内容，向右对齐 | `any` | -
errorCollect | 是否需要 `error-collect` | `boolean` | `false`
extra | 额外信息，向左对齐 | `string, TemplateRef<any>` | -
