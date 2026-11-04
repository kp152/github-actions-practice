# GitHub Actions 练习项目

欢迎来到本项目的文档站点！

本项目是开源软件设计与分析课程的实验二，主要内容是：

- 使用 **GitHub Actions** 实现 Python 项目的自动测试
- 使用 **MkDocs** 搭建文档站点
- 通过 **GitHub Pages** 自动部署文档网站

## 项目结构

    github-actions-practice/
    ├── calculator.py              # 计算器模块
    ├── test_calculator.py         # pytest 测试文件
    ├── mkdocs.yml                 # MkDocs 配置
    ├── docs/                      # 文档源码目录
    │   ├── index.md
    │   ├── about.md
    │   ├── guide.md
    │   └── api.md
    └── .github/workflows/
        ├── ci.yml                 # CI 测试工作流
        └── deploy.yml             # Pages 部署工作流

## 快速开始

克隆仓库后，本地运行测试：

    git clone https://github.com/KP152/github-actions-practice.git
    cd github-actions-practice
    pip install pytest
    pytest -v