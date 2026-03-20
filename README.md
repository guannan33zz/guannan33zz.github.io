# B-1368.github.io

个人主页（单文件 `index.html`，内嵌样式与脚本）。

## 部署

1. 在 GitHub 新建仓库，名称必须为 **`B-1368.github.io`**（与用户名一致）。
2. 把本文件夹内容推送到 `main` 分支根目录。
3. 仓库 **Settings → Pages**：Branch 选 **main**，文件夹 **/ (root)**。

站点地址：**https://b-1368.github.io**

```bash
cd B-1368.github.io
git init
git add index.html README.md
git commit -m "Add personal page"
git branch -M main
git remote add origin https://github.com/B-1368/B-1368.github.io.git
git push -u origin main
```

（若远程已有提交，先按 GitHub 页面提示拉取或改用 `git remote` 指向你的仓库。）
