# monologue1555.github.io

Monologue 的个人主页。纯静态页面，托管在 GitHub Pages。

访问地址：<https://monologue1555.github.io/>

## 页面内容

- 首页：个人介绍、名片、常用技术
- 项目：直播小助手、TeamFS、MiniOB 向量检索后端、AGENTS-Astra、never-lose-progress
- 工具箱：语言、方向、工作习惯
- 关于：个人简介与小档案

## 本地预览

```bash
python -m http.server 4173
```

然后打开 <http://localhost:4173>。

## 文件结构

```text
index.html          页面内容
styles.css          样式
script.js           年份与导航高亮
assets/             图标、项目截图、社交卡片
.nojekyll           跳过 GitHub Pages 的 Jekyll 处理
```

## 更新

改完 `index.html` 或 `styles.css` 后提交到 `main`，GitHub Pages 会自动重新发布。
