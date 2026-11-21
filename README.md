# chart-tool
A simple online chart maker / 简单在线图表生成工具
一个纯前端的轻量级图表生成工具，单 HTML 文件，无需安装、无需后端，打开即用。

## 在线演示
👉 [https://zhaojunpu.github.io/chart-tool/](https://zhaojunpu.github.io/chart-tool/)

## 功能特性
- 支持折线图、柱状图、饼图、环形图
- 第一列为横轴类别，其余列为数值系列
- 支持逗号分隔数据，也可直接从 Excel / WPS 表格复制粘贴
- 图表标题可自定义，参数可调
- 支持导出 PNG / JPG 图片，可复制到剪贴板
- 纯前端实现，无任何依赖，离线可用

## 使用方法
1. 直接下载然后打开 `index.html` 文件，或访问在线演示地址
2. 在数据源区域粘贴或输入表格数据（首行为表头）
3. 选择图表类型，填写图表标题
4. 点击「生成图表」，在右侧预览并调整参数
5. 导出 PNG / JPG 或直接复制图片


## 技术说明
- 纯 HTML + CSS + JavaScript 单文件实现
- 无框架、无第三方依赖
- 可直接部署到 GitHub Pages 等静态托管平台
