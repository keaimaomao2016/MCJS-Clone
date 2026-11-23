# MC 网页版中文整合站

免安装、中文、浏览器直接玩 Minecraft 的静态导航站。UI 参考 MCJS.Link 暗色风格。

## 文件

- `index.html` — 首页（引用 style.css）
- `style.css` — 样式
- `README.md` — 本文件

## 本地预览

双击 `index.html` 即可看页面；因 `href` 全部为外链，无需本地服务器。

## 部署到 GitHub Pages

1. 新建仓库，把这三个文件推上去
2. Settings → Pages → Source 选 `main` 分支 + `/root`
3. 访问 `https://<用户名>.github.io/<仓库名>/`

## 需要你确认的地方

- 所有「开始游戏」按钮目前统一指向 `https://mcjs.link`（占位）。
  拿到各版本真实入口后，把 `index.html` 里对应的 `href` 换成具体链接即可。
- 「更远古版本」（Beta / Alpha / Indev）指向 `https://eaglercraft.com`，非 MCJS 托管。
- 联系方式已按要求改为邮件：`1709174036@qq.com`

## 声明

本站仅为 Eaglercraft 开源项目及 MCJS 汉化成果的收录导航，非官方、不托管游戏文件、不提供离线下载、不用于商业用途。
