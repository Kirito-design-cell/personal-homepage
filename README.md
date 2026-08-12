# 个人主页

这是一个无需构建步骤的静态网站。上线前请在 `index.html` 中替换：

- `你的名字`、`YN` 和首页介绍文字
- `hello@example.com`
- GitHub、LinkedIn、X / Twitter 链接
- 三个项目的名称、描述和链接

## 部署到 Cloudflare Pages

在本目录执行：

```powershell
npx wrangler login
npx wrangler pages deploy . --project-name=你的项目名
```

首次部署会创建 Pages 项目；成功后访问 `https://你的项目名.pages.dev`。

也可以将本文件夹拖入 Cloudflare Dashboard 的 Workers & Pages → Create application → Drag and drop your files。
