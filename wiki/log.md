# Wiki 更新日志

追加式时间线。每次收录资料、整理查询、健康检查或重要修订后追加记录，不覆盖历史条目。

## [2026-10-09] ingest | 实验室技术知识库文档写入规范

- 建立 MkDocs 文档站与六类知识入口。
- 根据项目、课程、技术模块、问题记录与复盘要求建立模板。
- 按 Karpathy LLM Wiki 思路设置 sources、wiki、索引与日志维护约定。
- 原始规范保存在仓库根目录：`实验室技术知识库文档写入规范.md`。

## [2026-10-09] catalog | 明确总目录与部门正文仓库的分工

- 将主仓库定位调整为整本书的总目录和入口站。
- 各部门继续在自己的 GitHub 仓库维护正文；本仓库只登记章节、来源链接和导航摘要。
- 部门仓库链接待成员提供后补入分类目录。

## [2026-10-09] catalog | 亚博智能小车学习模块

- 新增学习课程模块「亚博智能小车」（ROSMASTER M3 PRO）学习指南，位于 `docs/知识体系/学习课程/亚博智能小车/index.md`。
- 正文来源登记为 Yahboom 官方教程仓库 <https://github.com/YahboomTechnology/ROSMASTER-M3PRO>；本仓库只保留学习路线与导航，不复制官方教程正文。
- 同步更新 mkdocs.yml 导航、学习课程目录页与 `sources/repositories.md` 外部来源表。

## [2026-10-10] catalog | 登记终端服务部章节仓库

- 登记部门：**终端服务部**（上海中侨大学 · 人工智能学院 · 具身智能研究所），维护账号 [@publieople](https://github.com/publieople)。
- 正文仓库 <https://github.com/publieople/lab-terminal-service>，在线阅读 <https://publieople.github.io/lab-terminal-service/>。
- 该仓库覆盖基础知识、技术模块、学习课程、项目实践、技术经验、历史与交接六个分类。各分类入口为**目录级 URL**，部门仓库新增或调整文档不会改变这些链接，本目录登记一次即可长期使用。
- 同步更新 `sources/repositories.md`（新增部门行与分类入口表）、`docs/知识体系/index.md`（分类状态与部门入口）、六个分类页（已登记章节）以及 `wiki/index.md`。
