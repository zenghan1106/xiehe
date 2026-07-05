# xiehe

GitHub Pages 项目站点占位仓库。

## 本地结构
- `index.html` —— 站点首页（当前为占位页，待替换真实内容）

## 部署到 GitHub Pages
1. 在 github.com 新建仓库，名称 `xiehe`，设为 Public
2. 本地推送到该仓库的 `main` 分支：
   ```bash
   cd xiehe
   git remote add origin https://github.com/<你的用户名>/xiehe.git
   git add .
   git commit -m "init xiehe site"
   git branch -M main
   git push -u origin main
   ```
3. 仓库 Settings → Pages → Source 选 `main` 分支 / `(root)` → Save
4. 稍等 1–2 分钟，访问 `https://<你的用户名>.github.io/xiehe`
