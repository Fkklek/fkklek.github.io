# 个人主页（GitHub Pages 静态网站）

一个极简的个人介绍单页网站，零依赖，可直接部署到 GitHub Pages。

## 文件说明
- `index.html`：页面结构，里面都是占位内容，按注释改成你自己的信息即可
- `styles.css`：样式，改颜色/字体都在 `:root` 里的变量
- `README.md`：本说明

## 部署到 GitHub Pages（3 步）

1. 在 GitHub 新建一个仓库，把这三个文件放进仓库根目录（`index.html` 必须在根目录）。
2. 打开仓库 **Settings → Pages**，Source 选 **Deploy from a branch**，分支选 **main**（或 master），目录选 **/ (root)**，保存。
3. 等一两分钟，访问 `https://你的用户名.github.io/仓库名/` 即可。

> 如果你想用 `用户名.github.io` 这种专属域名，把仓库名直接命名为 `你的用户名.github.io`，部署后访问 `https://你的用户名.github.io/`。

## 自定义提示
- 头像：把 `index.html` 里的 `<div class="avatar">YOU</div>` 换成 `<img class="avatar" src="头像地址" alt="头像" />`。
- 配色：改 `styles.css` 顶部 `:root` 里的 `--accent` 等变量即可整体换色。
- 内容：直接编辑 `index.html` 里的文字，所有占位都标了中文注释。
