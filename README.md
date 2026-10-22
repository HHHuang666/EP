# 把「电子社二轮硬件备考计划（基础版）」挂成永久手机 App（GitHub Pages）

这个文件夹里是做好的手机版清单（`index.html`，已含安装引导和 PWA 图标），配套 `manifest.webmanifest` 和三张小猫图标（`icon-180.png` / `icon-192.png` / `icon-512.png`）。
照下面步骤，它会变成一个**永久 https 网址**，任何手机都能「添加到主屏幕」当 App 用。

> ⚠️ 这是「基础版」，和之前的高级版（`Electronic-Club-plan` 仓库）是**两个独立仓库**。
> 建议本仓库名用 `Electronic-Club-plan-basic`（或其他不同英文名），别和高级版重名，否则会互相覆盖。

## 第 0 步：建免费 GitHub 账号（已有可跳过）
1. 打开 https://github.com ，点右上角 **Sign up**；
2. 填用户名 / 邮箱 / 密码；
3. 验证邮箱。不用绑卡、不用付费。

## 第 1 步：新建仓库（名字要和高级版不同）
1. 点右上角 **＋ → New repository**；
2. Repository name 填：`Electronic-Club-plan-basic`（或任意英文名，记住它）；
3. 选 **Public（公开）**——免费版只有公开仓库能开 Pages；
4. 勾 **Add a README file**；
5. 点 **Create repository**。

## 第 2 步：上传整个文件夹
1. 进仓库后点 **Add file → Upload files**；
2. 把本文件夹里的 **全部 5 个文件**（`index.html`、`manifest.webmanifest`、`icon-180.png`、`icon-192.png`、`icon-512.png`）一起拖进去；
3. 点 **Commit changes**。

## 第 3 步：开启 Pages
1. 仓库里点 **Settings → Pages**（左侧边栏，中文界面里叫「页面」）；
2. Branch 选 **main**，folder 选 **/ (root)**（中文界面里叫「上变角色」选 main）；
3. 点 **Save**。

## 第 4 步：等 1–2 分钟，拿到链接
你的永久网址是：
> https://**你的用户名**.github.io/**Electronic-Club-plan-basic**/

打开它，就是手机版清单。手机浏览器里点「分享 → 添加到主屏幕」，桌面就有小猫图标了。

## 以后更新
改了内容 → 把新的 `index.html`（以及如有改动 `manifest.webmanifest` / 图标）重新拖进仓库覆盖 → Commit。网址不变。

## 隐私说明
- 免费版必须选 **Public** 才能开 Pages，源码别人能看到；但网页本身只要知道链接就能打开（静态托管的天然限制，不是 GitHub 的问题）。
- 网页不会被搜索引擎收录，也不会挂在你 GitHub 主页，陌生人基本遇不到。
- 若还想「连链接被别人拿到也进不去」：可给 `index.html` 加一道 4 位 PIN 密码锁，打开需输入。
