# 星野远征 - GitHub Pages 发布版

这是一个纯前端 2D RPG 小游戏，不需要安装任何软件。

## GitHub 发布

这个文件夹已经整理成 GitHub Pages 网站根目录。

发布后，别人可以通过 GitHub Pages 网址直接打开游戏。

如果仓库名是 `starfield-rpg`，GitHub 用户名是 `rola2005-klc`，网址通常会是：

`https://rola2005-klc.github.io/starfield-rpg/`

## 文件

- `index.html`：完整游戏，单文件可运行
- `.nojekyll`：让 GitHub Pages 直接按静态网页发布
- `.github/workflows/deploy-pages.yml`：推送到 main 后自动部署

游戏不需要后端服务器，也不需要数据库。

## 操作

- 鼠标点击地图：移动角色
- 靠近 NPC 后点击对话按钮：对话
- 靠近怪物后点击攻击按钮：攻击
- 主要任务：击败史莱姆，获得经验并升级
