# Shuo Zhang 个人主页

这是基于 Academic Pages / Jekyll 搭建的个人主页项目，公开地址计划为：

https://llwhitez.github.io

## 内容结构

- `_pages/about.md`：首页
- `_pages/portfolio.html`：项目列表页
- `_pages/publications.html`：论文列表页
- `_pages/cv.md`：简历页
- `_portfolio/`：项目条目
- `_publications/`：论文条目
- `_config.yml`：站点标题、作者信息、社交链接等全局配置
- `images/profile.png`：侧边栏头像

## 本地运行

首次运行需要安装 Ruby 依赖：

```bash
bundle config --local path vendor/bundle
bundle install
bundle exec jekyll serve -l -H localhost
```

然后访问 `http://localhost:4000`。

## 更新内容

新增项目时，在 `_portfolio/` 目录中添加 Markdown 文件。新增论文时，在 `_publications/` 目录中添加 Markdown 文件。页面会在 Jekyll 构建时自动生成列表。

## 部署到 GitHub Pages

在 GitHub 上创建仓库：

```text
llwhitez.github.io
```

如果 GitHub owner 显示为 `llwhiteZ`，仓库名仍建议使用小写 `llwhitez.github.io`，这是 GitHub Pages 对用户主页的规范形式。将本仓库推送到 GitHub 后，项目中的 `.github/workflows/pages.yml` 会通过 GitHub Actions 自动构建并发布页面。

发布成功后，访问：

```text
https://llwhitez.github.io
```

搜索引擎收录需要页面已经公开上线，并且通常需要等待数天到数周。可以在 Google Search Console 中提交 `https://llwhitez.github.io/sitemap.xml` 加快发现。
