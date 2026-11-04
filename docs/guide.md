# 使用指南

## 本地运行测试

    pip install pytest
    pytest -v

## 本地预览文档

    pip install mkdocs-material
    mkdocs serve
    然后浏览器打开 http://127.0.0.1:8000

## 修改并发布文档

编辑 docs 目录下的 Markdown 文件后：

    git add .
    git commit -m "更新文档"
    git push origin main

推送后 GitHub Actions 会自动构建并部署到 Pages，稍等一两分钟就能在网站上看到更新。

## 常见问题

### Q: push 后 Actions 没反应？

检查工作流文件是否在 .github/workflows/ 目录下，文件名后缀是否为 .yml，以及触发条件是否匹配当前分支。

### Q: pytest 报 ModuleNotFoundError？

确保被测模块（如 calculator.py）在项目根目录下，pytest 默认从根目录开始找模块。