# AIlseekers.github.io

AI enthusiast and researcher, passionate about sharing little surprises.

陈奕好的个人站点，静态托管于 GitHub Pages（`main` 分支根目录）。

## 目录结构

| 路径 | 内容 |
| --- | --- |
| `/` | 站点导航（入口页） |
| `/portfolio/` | 个人主页 —— 项目 / 证书 / 简历 / 联系方式 |
| `/baoyan/` | 保研路线图 · 2028 届 · 上海 985/211 |
| `/index-old.html` | 旧版首页（归档保留） |
| `/form1.html`、`/school_web.html` | 早期页面（保留未改动） |

## 本地预览

```bash
python -m http.server 8000
```

打开 <http://localhost:8000/>。

## 维护说明

- **`.nojekyll` 不要删。** GitHub Pages 默认跑 Jekyll，会忽略下划线开头的目录，`portfolio/_astro/` 下的样式和脚本会全部 404。
- 页面里的 `canonical` / `og:url` / `og:image` 已按实际路径写好，改路径时记得同步。
- 站点为纯静态产物，无构建步骤，改完直接推送即可，Pages 会自动重新发布。
