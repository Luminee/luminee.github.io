# luminee.github.io

个人静态资源仓库：图片通过 **GitHub Pages** 托管，供外部引用（DSH 背景图、文档配图等）。

## 访问方式

同一份文件有三种取法，按场景选：

| 方式 | URL 格式 | 说明 |
|---|---|---|
| **GitHub Pages**（推荐） | `https://luminee.github.io/<路径>` | 稳定、走 CDN 缓存，适合直接填进页面/应用的图片链接 |
| raw 直链 | `https://raw.githubusercontent.com/Luminee/luminee.github.io/master/<路径>` | 原始文件，不加任何处理 |
| jsDelivr CDN | `https://cdn.jsdelivr.net/gh/Luminee/luminee.github.io@master/<路径>` | 国内通常更快（`@master` 会 301 跳到具体版本，浏览器可正常跟随） |

## 图片资源

| 文件 | 大小 | Pages 直链 |
|---|---|---|
| `pictures/illust_136567946_20260317_100249.png` | 4.9 MB | <https://luminee.github.io/pictures/illust_136567946_20260317_100249.png> |
| `pictures/0025.jpg` | 1.2 MB | <https://luminee.github.io/pictures/0025.jpg> |
| `pictures/p_wallpaper.jpg` | 426 KB | <https://luminee.github.io/pictures/p_wallpaper.jpg> |

## 新增一张图

1. 把文件放进 `pictures/`；
2. 提交并推送到 `master`；
3. 用上面的 URL 格式访问（Pages 构建后生效，通常几十秒内）。

## 注意

- 仓库是 **public**：任何拿到链接的人都能访问这些文件；
- 单文件过大（> 1 MB）时首次加载慢，需要的话先压缩或另存缩略图；
- 不要在此存放任何私密内容。