# 部门正文仓库清单

本表记录各部门负责维护的章节正文仓库。本仓库仅保存链接、目录元数据和状态，不复制正文。

| 部门 | 英文名 | 维护账号 | 章节或路径 | 正文仓库 | 状态 |
|---|---|---|---|---|---|
| 轮式机器人部 | Wheeled Robot Department | [@yukiiiii777](https://github.com/yukiiiii777) | 部门介绍、新生学习路线、VLA 入门讲义、OpenFlex 资源与手册精要、导航开发指南 | [yukiiiii777/robotics-department](https://github.com/yukiiiii777/robotics-department) | 已登记 |
| 工业设计部 | Industrial Design Department | [@TDFbyLEGO](https://github.com/TDFbyLEGO) | 基础知识、技术模块、学习课程、项目实践、技术经验、历史与交接（结构已初始化，正文待补充） | [TDFbyLEGO/lab-industrial-design](https://github.com/TDFbyLEGO/lab-industrial-design) | 已登记 |
| 机器狗部 | Quadruped Robot Department | [@shaokai-byte](https://github.com/shaokai-byte) | 技术模块：Unitree Go2 动作控制、相机识别；项目实践：YOLO11 目标检测训练全流程 | [shaokai-byte/go2](https://github.com/shaokai-byte/go2) | 已登记 |
| 终端服务部 | Terminal Service Department | [@publieople](https://github.com/publieople) | 参考、学习、项目、经验、历史与交接（2026-10-12 起） | [publieople/lab-terminal-service](https://github.com/publieople/lab-terminal-service) | 已登记 |
| 嵌入式开发部 | Embedded Systems Division | [@zz3304094520-ctrl](https://github.com/zz3304094520-ctrl) | 学习、设计图、历史、项目、资料五类目录（ESP32 教学与图纸、农业项目归档、开发板资料） | [zz3304094520-ctrl/embedded-development-pcb](https://github.com/zz3304094520-ctrl/embedded-development-pcb) | 已登记 |
| ROS 小车部 | ROS Robot Car Division | [@yukiiiii777](https://github.com/yukiiiii777)、[@Xinlanmy](https://github.com/Xinlanmy) | 学习课程：亚博智能小车（ROSMASTER M3 PRO）零基础学习指南 | [yukiiiii777/rosmaster-m3pro-guide](https://github.com/yukiiiii777/rosmaster-m3pro-guide) | 已登记 |

2026-10-20 实验室确认部门共六个，登记口径随之收敛：原「双足轮式机器人」「机械臂」两行取消——前者并入轮式机器人部（该部门的硬件是轮式双臂 OpenFlex Ultra 底盘，不是双足平台），后者的机械臂内容（PiPER 六轴）也写在同一部门仓库里。若后续另设双足平台部门，再单独增行，不预先占位。

其余部门对应的知识分类和章节范围需要收到仓库后再确认。添加链接时，请指向具体章节页面或仓库中的 README/目录，方便成员直接到达正文。

### 终端服务部 · 分类入口（2026-10-12 起）

部门总入口：<https://publieople.github.io/lab-terminal-service/部门/终端服务部/>

| 主书分类 | 部门仓库目录 | 入口 |
|---|---|---|
| 基础知识 | `参考/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/参考/> |
| 技术模块 | `参考/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/参考/> |
| 学习课程 | `学习/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/学习/> |
| 项目实践 | `项目/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/项目/> |
| 技术经验 | `经验/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/经验/> |
| 历史与交接 | `历史与交接/` | <https://publieople.github.io/lab-terminal-service/部门/终端服务部/历史与交接/> |

上表左侧是主书的六类目录，中间是该部门仓库里实际对应的目录。部门调整内部结构时，应同时更新本表与各分类页的链接——**分类名由主书统一，目录名由部门自定，两者用本表对齐**。

这些分类入口是**目录级 URL**：部门仓库里新增或调整文档不会改变这些链接，主书登记一次即可长期使用。

2026-10-12 说明：终端服务部把内部结构收敛为「四条内容线 + 记录 + 管理页」，原「基础知识」与「技术模块」两类合并为 `参考/`，「学习课程」「项目实践」「技术经验」分别改名为 `学习/`「项目」「经验」。链接已同步更新。

### 轮式机器人部 · 分类入口（2026-10-20 起）

部门总入口：<https://github.com/yukiiiii777/robotics-department>

该部门仓库按「编号文档」组织，不套用主书六类；下表左侧是主书分类，中间是该部门仓库里实际承载的文件。仓库未启用 GitHub Pages，入口指向 GitHub 上的文件页。

| 主书分类 | 部门仓库文件 | 入口 |
|---|---|---|
| 基础知识 | 暂无独立目录（概念与硬件说明见 `00-部门介绍.md`、前置知识见 `01-新生学习路线.md`） | [00 部门介绍](https://github.com/yukiiiii777/robotics-department/blob/main/docs/00-%E9%83%A8%E9%97%A8%E4%BB%8B%E7%BB%8D.md) |
| 技术模块 | `02-VLA入门讲义.md`、`03-OpenFlex资源汇总.md`、`04-OpenFlex-PI0.5数采训练推理手册精要.md`、`05-OpenFlex导航开发指南精要.md` | [02 VLA 入门讲义](https://github.com/yukiiiii777/robotics-department/blob/main/docs/02-VLA%E5%85%A5%E9%97%A8%E8%AE%B2%E4%B9%89.md) ｜ [03 资源汇总](https://github.com/yukiiiii777/robotics-department/blob/main/docs/03-OpenFlex%E8%B5%84%E6%BA%90%E6%B1%87%E6%80%BB.md) ｜ [04 数采训练推理手册精要](https://github.com/yukiiiii777/robotics-department/blob/main/docs/04-OpenFlex-PI0.5%E6%95%B0%E9%87%87%E8%AE%AD%E7%BB%83%E6%8E%A8%E7%90%86%E6%89%8B%E5%86%8C%E7%B2%BE%E8%A6%81.md) ｜ [05 导航开发指南精要](https://github.com/yukiiiii777/robotics-department/blob/main/docs/05-OpenFlex%E5%AF%BC%E8%88%AA%E5%BC%80%E5%8F%91%E6%8C%87%E5%8D%97%E7%B2%BE%E8%A6%81.md) |
| 学习课程 | `01-新生学习路线.md` | [01 新生学习路线](https://github.com/yukiiiii777/robotics-department/blob/main/docs/01-%E6%96%B0%E7%94%9F%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md) |
| 项目实践 | 暂无独立目录 | — |
| 技术经验 | 暂无独立目录 | — |
| 历史与交接 | `00-部门介绍.md`（部门沿革、硬件清单与三条主线） | [00 部门介绍](https://github.com/yukiiiii777/robotics-department/blob/main/docs/00-%E9%83%A8%E9%97%A8%E4%BB%8B%E7%BB%8D.md) |

补充说明：

- 硬件底座是 OpenFlex Ultra 轮式双臂机器人（27 自由度、自带 RTX 4090、MID360 激光雷达）、PiPER 六轴机械臂与 PICO 4 Ultra VR 一体机；三条主线是机械臂操作、VLA（视觉-语言-动作）与底盘导航（SLAM + Nav2）。
- `docs/06-招新演讲稿.md` 是部门宣传稿，不入六类，登记备查：[06 招新演讲稿](https://github.com/yukiiiii777/robotics-department/blob/main/docs/06-%E6%8B%9B%E6%96%B0%E6%BC%94%E8%AE%B2%E7%A8%BF.md)。
- `docs/pdf/` 存两份操作手册 PDF（数采训练推理、导航开发），是 04、05 两份精要的来源原件。
- 项目实践与技术经验暂无独立目录：当前内容以讲义与手册为主，等有项目记录与复盘后再补登记，不新建空目录。

### 工业设计部 · 分类入口（2026-10-15 起）

部门总入口：<https://github.com/TDFbyLEGO/lab-industrial-design>

该部门仓库尚未启用 GitHub Pages，下列入口指向 GitHub 上的目录页；路径里的中文按 URL 编码书写，浏览器与链接检查工具都能直接打开。

| 主书分类 | 部门仓库目录 | 入口 |
|---|---|---|
| 基础知识 | `docs/基础知识/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86> |
| 技术模块 | `docs/技术模块/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E6%8A%80%E6%9C%AF%E6%A8%A1%E5%9D%97> |
| 学习课程 | `docs/学习课程/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E5%AD%A6%E4%B9%A0%E8%AF%BE%E7%A8%8B> |
| 项目实践 | `docs/项目实践/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E9%A1%B9%E7%9B%AE%E5%AE%9E%E8%B7%B5> |
| 技术经验 | `docs/技术经验/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E6%8A%80%E6%9C%AF%E7%BB%8F%E9%AA%8C> |
| 历史与交接 | `docs/历史与交接/` | <https://github.com/TDFbyLEGO/lab-industrial-design/tree/main/docs/%E5%8E%86%E5%8F%B2%E4%B8%8E%E4%BA%A4%E6%8E%A5> |

该仓库 2026-10-15 初始化：六个分类目录与写作模板已建立，正文由部门成员核实后补充。部门报到文件见其仓库 `sources/实验室目录登记信息.md`。

### 嵌入式开发部 · 分类入口（2026-10-18 起）

部门总入口：<https://github.com/zz3304094520-ctrl/embedded-development-pcb>

该部门仓库按「学习、设计图、历史、项目、资料」五类组织，与主书六类不是一一对应；下表左侧是主书分类，中间是该部门仓库里实际承载的目录。仓库尚未启用 GitHub Pages，入口指向 GitHub 上的目录页。

| 主书分类 | 部门仓库目录 | 入口 |
|---|---|---|
| 基础知识 | `学习/` | <https://github.com/zz3304094520-ctrl/embedded-development-pcb/tree/main/%E5%AD%A6%E4%B9%A0> |
| 技术模块 | `设计图/`、`资料/` | <https://github.com/zz3304094520-ctrl/embedded-development-pcb/tree/main/%E8%AE%BE%E8%AE%A1%E5%9B%BE> |
| 学习课程 | `学习/` | <https://github.com/zz3304094520-ctrl/embedded-development-pcb/tree/main/%E5%AD%A6%E4%B9%A0> |
| 项目实践 | `项目/` | <https://github.com/zz3304094520-ctrl/embedded-development-pcb/tree/main/%E9%A1%B9%E7%9B%AE> |
| 技术经验 | 暂无独立目录 | 经验内容目前散见于 `项目/` 与 `历史/`，待部门确认后归并 |
| 历史与交接 | `历史/` | <https://github.com/zz3304094520-ctrl/embedded-development-pcb/tree/main/%E5%8E%86%E5%8F%B2> |

补充说明：

- `资料/` 另存开发板参考手册、驱动、通用固件与部门介绍文档，属参考资料性质，按主书约定归入「技术模块」一侧。
- 「技术经验」一类暂不新建目录：该部门现有内容的经验部分写在项目记录与历史归档里，强行拆目录会造成同一份材料两处维护；待部门自行划分后再补登记。
- 仓库 2026-10-17 完成首轮整理（ESP32 教学与图纸、慧田智测/温室控制/单轨播种机归档、OLED 与电机资料）。早期 2026-10-13 至 10-17 之间仓库为私有状态，链接检查曾报 404；现已公开，本表状态改为已登记。

## 外部资料来源

非部门维护、但被目录引用的外部资料仓库。仅登记链接与用途，不复制正文。

| 来源 | 类型 | 用途 | URL | 状态 |
|---|---|---|---|---|
| YahboomTechnology/ROSMASTER-M3PRO | 厂商官方教程仓库 | 亚博智能小车学习模块的正文来源（23 类课程 PDF） | https://github.com/YahboomTechnology/ROSMASTER-M3PRO | 已登记 |
