# 提示词工作台

本地提示词管理工具，模块化构建和管理 LLM 提示词。

## 功能

- 模块化编辑：Role / Context / Task / Constraints / Format 五模块结构
- 实时预览拼接结果，一键复制
- 分类管理与搜索筛选
- 本地 JSON 文件存储，支持双向同步
- 深色/浅色主题自适应

## 使用

1. 双击 `index.html` 用 Chrome/Edge 打开
2. 点击「打开」选择 JSON 文件，或「新建文件」创建
3. 编辑提示词，Ctrl+S 保存

## 技术栈

- Vue 3 (CDN)
- Material Web (Google Material Design 3)
- File System Access API

## 浏览器要求

Chrome 86+ / Edge 86+（需支持 File System Access API）
