# Aiden Wu — Frontend Developer Résumé

在线简历 / Live résumé，部署于 GitHub Pages。

纯静态单文件页面，**无构建步骤、无依赖、无第三方脚本与统计代码**；仅一段十余行原生 JS，用于在浏览器中还原邮箱地址（防爬虫抓取，禁用 JS 时降级为可读的 `[at]` 写法）。

- 打开 `index.html` 查看网页版，右上角可下载 `aid-cv.pdf`
- `aid-cv.pdf` 为同一份源码打印导出的 A4 两页版本，改动后会同步重新生成
- 版式与分页由 `@page` 固定，浏览器直接打印（Ctrl / Cmd + P）结果与 PDF 一致
- 移动端按 794px 布局视口整页缩放，无需横向滚动
