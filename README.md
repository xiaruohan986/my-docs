# my-docs

使用 MkDocs + Material 主题构建的技术文档，通过 GitHub Actions 自动部署到 GitHub Pages。

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

访问 http://127.0.0.1:8000 即可预览。

## 部署方式

推送 `main` 分支后，GitHub Actions 会自动运行 `.github/workflows/deploy.yml`，将 `site/` 目录部署到 `gh-pages` 分支。

文档地址：https://xiaruohan986.github.io/my-docs/
