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

## [2026-10-11] revise | 亚博智能小车学习指南：章节直达链接与状态升级

- 8 阶段路线表中所有官方章节名改为直达 Yahboom 教程仓库对应课程目录的链接（目录路径已逐一通过 API 核对存在），成员可一步到达正文。
- 指南状态由「草稿」升级为「已核实」，维护日期更新为 2026-10-11；同步更新学习课程目录页状态。
- 仍遵守「只登记、不复制正文」约定，未复制任何官方教程内容。

## [2026-10-12] catalog | 登记机器狗与 ROS 小车仓库，并同步终端服务部 v2 结构

- 新登记部门仓库：**机器狗** [shaokai-byte/go2](https://github.com/shaokai-byte/go2)（维护账号 [@shaokai-byte](https://github.com/shaokai-byte)，Unitree Go2 二次开发：动作控制、相机识别、YOLO11 目标检测训练全流程）；**ROS 小车** [yukiiiii777/rosmaster-m3pro-guide](https://github.com/yukiiiii777/rosmaster-m3pro-guide)（维护账号 [@yukiiiii777](https://github.com/yukiiiii777)，亚博智能小车 ROSMASTER M3 PRO 零基础学习指南）。
- 同步更新 `sources/repositories.md`（部门行 + 分类入口表）、`docs/知识体系/index.md`（部门入口表与分类状态）、技术模块 / 学习课程 / 项目实践三个分类页，以及 `wiki/index.md`。
- **修复失效链接**：终端服务部 2026-10-12 起把仓库内部结构收敛为「四条内容线 + 记录 + 管理页」，原「学习课程」「项目实践」「技术经验」改名为 `学习/`「项目」「经验」，「基础知识」与「技术模块」合并为 `参考/`。原先登记的 5 个分类入口 URL 已全部 404，本次按新目录更新，并在 `sources/repositories.md` 增加「主书分类 ↔ 部门仓库目录」对应表，便于以后核对。
- 分类名仍由主书统一为六类，部门仓库内部目录自定，两者用对应表对齐。

## [2026-10-15] catalog | 登记工业设计部仓库

- 登记部门：**工业设计**，维护账号 [@TDFbyLEGO](https://github.com/TDFbyLEGO)，正文仓库 <https://github.com/TDFbyLEGO/lab-industrial-design>。该仓库 2026-10-15 初始化，六个分类目录与写作模板已建立，正文待部门补充。
- 六个分类入口按**目录级 URL** 登记（`docs/基础知识/`、`docs/技术模块/`、`docs/学习课程/`、`docs/项目实践/`、`docs/技术经验/`、`docs/历史与交接/`）。该仓库尚未启用 GitHub Pages，入口指向 GitHub 目录页，URL 里的中文路径段按 URL 编码书写。
- 同步更新 `sources/repositories.md`（该部门行由「待登记」升级为「已登记」，并新增分类入口表）、`docs/知识体系/index.md`（部门入口与分类说明）、六个分类页，以及 `wiki/index.md` 与 `docs/wiki/index.md`。
- 未复制任何正文；登记前仓库首页与六个目录链接均已实测可访问。
