# AI 静态页面项目集

用于存放多个独立的 AI 静态页面项目，每个项目使用自己的文件夹。

## 项目

| 项目 | 目录 | 在线访问 |
| --- | --- | --- |
| AI专业研究生择校指南 | `ai-graduate-guide/` | [打开页面](https://sidfate.github.io/ai-html/ai-graduate-guide/) |

[项目首页](https://sidfate.github.io/ai-html/)

## GitHub Pages

发布源为 `main` 分支的根目录 `/`。根目录的 `index.html` 是项目导航页，`.nojekyll` 用于直接发布静态文件。

新增项目时创建独立文件夹，将入口文件命名为 `index.html`，并在根目录导航页添加链接。项目内的资源使用相对路径，例如 `./assets/style.css`。

推送到 `main` 后会自动更新，各项目的地址为 `https://sidfate.github.io/ai-html/<项目文件夹>/`。
