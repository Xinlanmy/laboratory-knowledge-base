# 实验室技术知识库总目录

这是实验室整本技术书的目录与入口站。**各部门的章节正文继续维护在对应部门负责人的 GitHub 仓库中；本仓库只登记目录、仓库链接、来源关系和维护规范，不复制正文。**

**在线阅读：** GitHub Pages 发布完成后可从仓库主页访问。

## 开始阅读

- [知识库首页](docs/index.md)
- [全书目录](docs/知识体系/index.md)
- [贡献与维护指南](docs/关于知识库/贡献指南.md)
- [文档写入规范](实验室技术知识库文档写入规范.md)
- [LLM Wiki 索引](wiki/index.md)
- [更新日志](wiki/log.md)
- [部门正文仓库清单](sources/repositories.md)

目前纳入目录的部门：机器狗、双足轮式机器人、ROS 小车、工业设计、机械臂、嵌入式开发。各部门仓库地址待提供，见[仓库清单](sources/repositories.md)。

## 目录

```text
docs/       总目录网站、阅读导航和维护规范
sources/    各部门章节仓库的来源登记，不存放章节正文
wiki/       LLM Wiki 风格的目录索引与更新日志
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

仓库配置为使用 GitHub Actions 构建与发布。推送到 `main` 后，工作流会构建总目录并发布到 Pages。

项目来源： [Andrej Karpathy 的 LLM Wiki 思路](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)；本仓库结合实验室技术文档规范进行适配。
