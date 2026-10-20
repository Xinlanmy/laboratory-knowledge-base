# Wiki 索引

本索引是全书总目录的 LLM Wiki 入口。正文保存在部门负责人的独立 GitHub 仓库；这里只保留可追溯链接、分类和导航摘要。详细约定见根目录 `AGENTS.md`。

## 实验室知识体系

- [基础知识](../docs/知识体系/基础知识/index.md) — 已登记：终端服务部（终端与命令行、计算机基础、开发经验，见其仓库 `参考/`）、工业设计部（分类入口已建立，正文待补充）、嵌入式开发部（ESP32 与 Arduino 入门，见其仓库 `学习/`）；轮式机器人部暂无独立目录，前置知识在其 `01-新生学习路线.md`。
- [技术模块](../docs/知识体系/技术模块/index.md) — 已登记：终端服务部（Tailscale 组网、Agent 平台部署、监控与备份等，见其仓库 `参考/`）、机器狗部（Unitree Go2 动作控制与相机识别）、工业设计部（正文待补充）、嵌入式开发部（设计图与资料）、轮式机器人部（VLA 入门讲义、数采训练推理与导航开发指南精要）。
- [学习课程](../docs/知识体系/学习课程/index.md) — 已登记：[亚博智能小车学习指南（ROSMASTER M3 PRO）](../docs/知识体系/学习课程/亚博智能小车/index.md)（[ROS 小车部仓库](https://github.com/yukiiiii777/rosmaster-m3pro-guide)）、终端服务部学习路径与课程、工业设计部与嵌入式开发部（待整理成课程序列）、轮式机器人部新生学习路线；正文来源以各部门仓库为准。
- [项目实践](../docs/知识体系/项目实践/index.md) — 已登记：终端服务部（设备与 Agent 统一管理，正文补充中）、机器狗部（[YOLO11 目标检测训练流程](https://github.com/shaokai-byte/go2)）、工业设计部（正文待补充）、嵌入式开发部（五个项目）；轮式机器人部暂无独立目录。
- [技术经验](../docs/知识体系/技术经验/index.md) — 已登记：终端服务部（3 篇排障复盘，见其仓库 `经验/`）、工业设计部（正文待补充）；其余部门暂无独立目录。
- [历史与交接](../docs/知识体系/历史与交接/index.md) — 已登记：终端服务部（2025 年秋季教学进度）、工业设计部（正文待补充）、嵌入式开发部（历史归档）、轮式机器人部（部门介绍与硬件清单）。

## 规范与维护

- [登记与引用规范（v2）](../docs/关于知识库/登记与引用规范.md) — 本仓库唯一权威的结构与登记约定：登记字段、状态枚举、URL 规则、分类对应表。v1《文档写入规范》[已归档](../docs/归档/实验室技术知识库文档写入规范-v1.md)。
- [贡献指南](../docs/关于知识库/贡献指南.md) — 收录、审核和发布流程。

## 部门正文仓库

六个已登记部门，名称按 2026-10-20 实验室确认的正式称呼排列：

1. **轮式机器人部（Wheeled Robot Department）** —— 仓库 [yukiiiii777/robotics-department](https://github.com/yukiiiii777/robotics-department)。2026-10-19 起按编号文档组织：00 部门介绍、01 新生学习路线、02 VLA 入门讲义、03 OpenFlex 资源汇总、04 数采训练推理手册精要、05 导航开发指南精要、06 招新演讲稿，`docs/pdf/` 另存两份手册；未套用主书六类，对应关系见[部门正文仓库清单](../sources/repositories.md)。硬件为 OpenFlex Ultra 轮式双臂 + PiPER 六轴机械臂 + PICO 4 Ultra，三条主线是机械臂操作、VLA、底盘导航。该仓库尚未启用在线阅读站点。

2. **工业设计部（Industrial Design Department）** —— 仓库 [TDFbyLEGO/lab-industrial-design](https://github.com/TDFbyLEGO/lab-industrial-design)。2026-10-15 初始化，六个分类入口已建立、正文待补充；尚未启用在线阅读站点。

3. **机器狗部（Quadruped Robot Department）** —— 仓库 [shaokai-byte/go2](https://github.com/shaokai-byte/go2)（Unitree Go2 二次开发：动作控制、相机识别、YOLO11 目标检测训练）。

4. **终端服务部（Terminal Service Department）** —— 仓库 [publieople/lab-terminal-service](https://github.com/publieople/lab-terminal-service)，在线阅读 [publieople.github.io/lab-terminal-service](https://publieople.github.io/lab-terminal-service/)。2026-10-12 起内部结构为四条内容线 + 记录 + 管理页（`参考`、`学习`、`项目`、`经验`、`历史与交接`）。

5. **嵌入式开发部（Embedded Systems Division）** —— 仓库 [zz3304094520-ctrl/embedded-development-pcb](https://github.com/zz3304094520-ctrl/embedded-development-pcb)。2026-10-13 建立、10-17 完成首轮整理后公开；按学习、设计图、历史、项目、资料五类组织，不套用主书六类；尚未启用在线阅读站点。

6. **ROS 小车部（ROS Robot Car Division）** —— 仓库 [yukiiiii777/rosmaster-m3pro-guide](https://github.com/yukiiiii777/rosmaster-m3pro-guide)（亚博智能小车 ROSMASTER M3 PRO 零基础学习指南，正文指向 Yahboom 官方教程仓库）。

各部门的分类入口与目录级 URL 见[部门正文仓库清单](../sources/repositories.md)。这里只维护来源元数据和导航摘要，不存放正文。
