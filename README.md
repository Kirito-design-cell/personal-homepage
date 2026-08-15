# 可乐的个人主页

这是一个无需构建步骤的静态网站，托管在 Cloudflare Pages，并通过 GitHub 自动部署。

- 线上地址：https://personal-homepage-e0n.pages.dev
- GitHub 仓库：https://github.com/Kirito-design-cell/personal-homepage

## 如何更新

修改本目录中的 `index.html`、`styles.css`、`script.js`，然后提交推送：

```powershell
git add .
git commit -m "更新内容说明"
git push
```

Cloudflare 会自动重新构建并发布，约 1 分钟后生效。
