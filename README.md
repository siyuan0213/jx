# 浪漫爱心雨

一个单文件的中文爱心雨页面。打开页面，点一下按钮，就会落下一场爱心雨。

## 文件

- `index.html` — 网站首页（GitHub Pages 默认打开这个文件）
- `jyx.html` — 同一页面的备份文件名
- `.nojekyll` — 告诉 GitHub Pages 不要用 Jekyll 处理静态文件

## 本地预览

直接双击 `index.html` 即可，或在文件夹里运行：

```powershell
python -m http.server 8766
```

然后打开 <http://127.0.0.1:8766/>。

## 部署

发布到 GitHub Pages 的 `main` 分支根目录。站点发布后，仓库的 Pages 地址即为公开访问地址。
