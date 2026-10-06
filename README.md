# 《蝶归》项目网站

静态网站，无需构建工具，可直接部署到 GitHub Pages。

## 本地预览

直接打开 `index.html`，或在当前目录运行任意静态服务器。

## GitHub Pages

1. 将 `website` 目录中的全部文件提交到 GitHub 仓库。
2. 在仓库 **Settings → Pages** 中选择从分支部署。
3. 选择 `main` 分支和根目录，保存后等待生成访问地址。

## 内容更新

- 页面文字：编辑 `index.html`
- 色彩和版式：编辑 `styles.css`
- 图片和视频：替换 `assets` 内同名文件
- 点位二维码：替换 `assets/qrs` 内对应图片

地图与五个二维码已从 Figma 设计稿单独导出。当前 Figma 中研学基地明信片背面没有放置二维码，网站以临时图和“待补齐”提示标记；补充后替换 `assets/qrs/research-placeholder.png` 即可。
