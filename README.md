# 实验室技术知识库

面向实验室成员的持续更新技术手册：从基础知识、技术模块和课程，到可复现项目、技术经验与历史交接。

**在线阅读：** GitHub Pages 发布完成后可从仓库主页访问。

## 开始阅读

- [知识库首页](docs/index.md)
- [知识体系与目录](docs/知识体系/index.md)
- [贡献与维护指南](docs/关于知识库/贡献指南.md)
- [文档写入规范](实验室技术知识库文档写入规范.md)
- [LLM Wiki 索引](wiki/index.md)
- [更新日志](wiki/log.md)

## 目录

```text
docs/       面向成员阅读的 MkDocs 网站内容
sources/    原始资料存档；入库后不覆盖原件
wiki/       从资料中整理出的互链知识页、索引和维护日志
templates/  技术模块、课程、项目、问题复盘模板
```

知识条目应注明来源；修正重要结论时保留依据并更新相关链接。详见根目录的[文档写入规范](实验室技术知识库文档写入规范.md)。

## 本地预览

需要 Python 3.10 或更新版本：

```bash
python -m pip install -r requirements.txt
mkdocs serve
```

## GitHub Pages

仓库配置为使用 GitHub Actions 构建与发布。推送到 `main` 后，工作流会构建 `site/` 并发布到 Pages。首次启用时，在仓库 **Settings → Pages → Build and deployment** 选择 **GitHub Actions**。

项目来源： [Andrej Karpathy 的 LLM Wiki 思路](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)；本仓库结合实验室技术文档规范进行适配。
