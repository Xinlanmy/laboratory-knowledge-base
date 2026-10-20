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

## [2026-10-12] revise | 规范正本化：登记与引用规范 v2，并启用第一层链接门

- 结构与登记约定重写为《登记与引用规范（v2）》，正本唯一：`docs/关于知识库/登记与引用规范.md`。原 v1《文档写入规范》全文归档到 `docs/归档/实验室技术知识库文档写入规范-v1.md`，只作对照。
- 去重：此前同一份规范存在三份副本（仓库根目录、`docs/关于知识库/`、`docs/wiki/`），根目录与 `docs/关于知识库/` 两份逐字节相同、`docs/wiki/` 那份已经开始漂移。现在这两处改为指向正本的入口页，旧路径继续可用。
- 去重：写作模板此前有 `templates/` 与 `docs/写作模板/` 两份，其中技术模块、课程两份模板内容已不一致。正本统一为 `docs/写作模板/`，`templates/` 四个文件改为入口页。
- 新增 `.github/workflows/link-check.yml`（第一层链接门）：PR 与推送到 `main` 时检查所有 Markdown 外链（lychee，接受 200/206/429/503，404/410/403 视为失败），每天 UTC 01:00 定时跑一次，定时失败自动开 Issue 并附报告。
- 启用前实测全库 48 条外链，全部可达，因此排除清单为空。
- 同步更新 `AGENTS.md`、`README.md`、`docs/index.md`、两处 Wiki 索引、贡献指南与 `mkdocs.yml` 导航。
## [2026-10-15] catalog | 登记工业设计部仓库

- 登记部门：**工业设计**，维护账号 [@TDFbyLEGO](https://github.com/TDFbyLEGO)，正文仓库 <https://github.com/TDFbyLEGO/lab-industrial-design>。该仓库 2026-10-15 初始化，六个分类目录与写作模板已建立，正文待部门补充。
- 六个分类入口按**目录级 URL** 登记（`docs/基础知识/`、`docs/技术模块/`、`docs/学习课程/`、`docs/项目实践/`、`docs/技术经验/`、`docs/历史与交接/`）。该仓库尚未启用 GitHub Pages，入口指向 GitHub 目录页，URL 里的中文路径段按 URL 编码书写。
- 同步更新 `sources/repositories.md`（该部门行由「待登记」升级为「已登记」，并新增分类入口表）、`docs/知识体系/index.md`（部门入口与分类说明）、六个分类页，以及 `wiki/index.md` 与 `docs/wiki/index.md`。
- 未复制任何正文；登记前仓库首页与六个目录链接均已实测可访问。

## [2026-10-18] catalog | 登记嵌入式开发部仓库

- 登记部门：**嵌入式开发与 PCB 板**，维护账号 [@zz3304094520-ctrl](https://github.com/zz3304094520-ctrl)，正文仓库 <https://github.com/zz3304094520-ctrl/embedded-development-pcb>。该仓库 2026-10-13 建立，10-17 完成首轮整理后转为公开；此前登记受阻是仓库处于私有状态，匿名访问返回 404，与仓库是否真实存在无关。
- 该部门未套用主书六类，按「学习、设计图、历史、项目、资料」五类组织。本次在 `sources/repositories.md` 增加「主书分类 ↔ 部门仓库目录」对应表：基础知识与学习课程指向 `学习/`，技术模块指向 `设计图/` 与 `资料/`，项目实践指向 `项目/`，历史与交接指向 `历史/`。
- 「技术经验」一类没有对应目录：该部门的排障与复盘写在项目记录和历史归档里，拆新目录会造成同一份材料两处维护，因此分类页写明现状与待办，未新建目录、未虚构条目。
- 五个目录入口按目录级 URL 登记，中文路径段按 URL 编码书写；登记前六个链接（仓库首页与五个目录）逐一实测返回 200。
- 同步更新 `sources/repositories.md`、`docs/知识体系/index.md`（部门入口、分类状态与登记说明）、六个分类页、`docs/index.md`、`README.md`、`wiki/index.md` 与 `docs/wiki/index.md`。

## [2026-10-20] catalog | 部门目录改版：六个部门正式名称与轮式机器人部登记

- 部门名单自 2026-10-20 起固定为六个（中英文对照）：轮式机器人部（Wheeled Robot Department）、工业设计部（Industrial Design Department）、机器狗部（Quadruped Robot Department）、终端服务部（Terminal Service Department）、嵌入式开发部（Embedded Systems Division）、ROS 小车部（ROS Robot Car Division）。`sources/repositories.md` 主表新增「英文名」列，按此顺序排列。
- 新增登记：**轮式机器人部** —— 仓库 <https://github.com/yukiiiii777/robotics-department>（2026-10-19 建立并推送）。该仓库按编号文档组织（00 部门介绍、01 新生学习路线、02 VLA 入门讲义、03 OpenFlex 资源汇总、04 数采训练推理手册精要、05 导航开发指南精要、06 招新演讲稿，`docs/pdf/` 另存两份手册），未套用主书六类，故新增「主书分类 ↔ 部门文档」对应表：基础知识指向 00 与 01，技术模块指向 02–05，学习课程指向 01，历史与交接指向 00；项目实践与技术经验暂无对应文档，写明现状未新建目录。该仓库尚未启用 GitHub Pages，入口均指向 blob URL。
- 取消原「双足轮式机器人」「机械臂」两行：前者与轮式机器人部是同一部门的不同叫法，后者是该部门的硬件之一（PiPER 六轴机械臂），不单列为部门；若日后另设双足部门再增行。合并后部门总数为六，与实验室口径一致。
- 部门名称统一为官方全称：登记表与六个分类页中的「工业设计」「机器狗」「嵌入式开发」「ROS 小车」分别改为「工业设计部」「机器狗部」「嵌入式开发部」「ROS 小车部」。
- 同步更新 `sources/repositories.md`、`docs/知识体系/index.md`（分类状态表、登记说明、部门入口表）、六个分类页、`docs/index.md`、`README.md`、`wiki/index.md` 与 `docs/wiki/index.md`。
- 登记前实测：仓库首页与七个文档 blob URL 均返回 200；两次 curl 返回 000 是代理抖动，改用 GitHub API 确认仓库已公开。
- 补记：ROS 小车部清单补充共同维护账号 [@yukiiiii777](https://github.com/yukiiiii777) 与 [@Xinlanmy](https://github.com/Xinlanmy)。
