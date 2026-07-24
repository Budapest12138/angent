# 碑帖智能体

基于 Vue2 + Element UI 的上海图书馆典籍智能体，参加智能体竞赛项目。

## 技术栈
- Vue 2.7 (CDN)
- Element UI (CDN)
- 原生 CSS 动画

## 如何运行
直接用浏览器打开 `index.html` 即可。

## 项目结构
- `index.html`：首页，含卷轴开屏动画和功能菜单
- `page1.html`：核心简介页，展示碑帖信息
- `images/`：所有图片资源
- `public/`：卷轴左右背景图

## 后续开发建议
- 如需修改统计数字，找到 `page1.html` 中 `targetNums` 变量
- 如需调整颜色，找到 `index.html` 中 `.strip-bg` 对应的渐变色值
- 如需对接后端 API，可在 Vue 的 methods 中添加 axios/fetch 请求
