# ESGAgent-webpage

极简静态网页框架，通过 GitHub Actions 自动部署到 GitHub Pages。

## 结构

```
index.html            页面骨架（导航 / Hero / About / Features / Demo / Contact / Footer 占位区块）
assets/css/style.css  样式
assets/js/main.js     脚本
.github/workflows/deploy.yml  自动部署工作流
```

无需构建工具，纯 HTML/CSS/JS，后续可直接在 `index.html` 里填充正式内容。

## 部署方式（首次需手动开启一次）

1. 打开仓库 Settings → Pages
2. Source 选择 **GitHub Actions**
3. push 到 `main` 分支后，工作流会自动构建并发布

部署完成后可通过 `https://elainezhao92.github.io/ESGAgent-webpage/` 访问。

## 本地预览

直接用浏览器打开 `index.html`，或者：

```bash
python3 -m http.server
```
