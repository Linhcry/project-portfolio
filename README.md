# 刘琦的项目档案

**机器人 / 控制 / 算法 / 工程平台**。按项目资料时间整理具体工作、实现与可检查的结果。最近更新：**2026-11-10**。

## 最近更新

- **[Super Hand](https://github.com/Linhcry/super-hand-showcase)**：五指灵巧操作与机器人书写的当前技术展示，补齐架构、控制规划、模型卡、学习迭代和仿真录像。源码与设备标定保持私有。
- **[冶炼分析平台 2.0.1](https://github.com/Linhcry/smelter-analytics-platform)**：新增原生 Qt 桌面源码、预测缓存及两组 ResNet 研究；图像与日期标签的验证结果保留原分母，默认仍为原稳健 PLS。
- **[中文教学动画工作台](docs/teaching-video-workbench.md)**：约三分钟课程、Manim/三维/真实素材、自然男声与双语字幕；完整流程已独立重建验证。
- **[海陆空机械宠物 P32C](https://github.com/Linhcry/modular-robot-pet/blob/main/docs/P32C进展-20261110.md)**：新增三态概览、质量与动力学诊断。完整快速步态、传动及真机性能仍在研发。
- **[轮毂装堵与抓取学习](docs/automotive-wheel-embodied-intelligence.md)**：整理产线、机械分类供料、乱堆抓取与整箱连续任务各自的结果。
- **[本科毕设](https://github.com/Linhcry/parcel-sorting-arm-design)**：当前分支移除整机和零件 STEP 原模型，保留结构图片、有限元图及设计摘要。

## 项目时间线

| 资料时间 / 阶段 | 项目 | 主要工作 | 当前材料 |
|---|---|---|---|
| 本科期间 · 2024 年归档线索 | [太阳能小车](https://github.com/Linhcry/solar-car-mechanical-design) | 整车方案、结构、凸轮机构与参数匹配 | CAD、计算表 |
| 2026-04 | [PVC 凝胶仿生鱼尾](docs/pvc-fish-tail.md) | 本科团队的柔性驱动路线与汇报 | 团队项目简介 |
| 2026-05—06 | [分拣机械臂毕设](https://github.com/Linhcry/parcel-sorting-arm-design) | 机构、伺服/传动、轴系与静力分析 | 图片与设计摘要 |
| 2026-07 起 | [RoboCup T1](https://github.com/Linhcry/robocup-t1-control-lab) | 23 DoF 控制、步态、PPO 与起身评测 | 仿真程序与实验记录 |
| 2026-08 起 | [机器人舞蹈平台](https://github.com/Linhcry/robot-motion-platform) | 动捕、重定向、编排与诊断 | 平台与算法适配 |
| 2026-09 起 | [机械宠物设计](https://github.com/Linhcry/modular-robot-pet) | SolidWorks 自动化、接口、三态机构与载荷/动力学筛选 | P32C 候选及检查记录 |
| 2026-09 起 | [早期灵巧手书写](https://github.com/Linhcry/dexhand-calligraphy) → [Super Hand](https://github.com/Linhcry/super-hand-showcase) | OCR/笔画、IK、接触、RGB-D、多阶段工具操作及学习 | 历史程序、当前技术展示 |
| 2026-09 | [无人机联合优化](https://github.com/Linhcry/uav-disaster-optimization) | 分配、路径、充电、通信与独立验证 | 算法与建模程序 |
| 2026-10 起 | [冶炼分析平台](https://github.com/Linhcry/smelter-analytics-platform) | 图像回归、数据管理、训练评估、Qt 桌面和现场接口 | 2.0.1 源码；现场指标待验证 |
| 2026-10 | [轮毂与抓取仿真](docs/automotive-wheel-embodied-intelligence.md) | 装堵、机械供料、接触恢复、PPO/MPC | 仿真证据摘要，代码私有 |
| 2026-10—11 | [教学动画与制作工作台](docs/teaching-video-workbench.md) | 文案、真实素材、配音字幕、Manim、三维与合成 | 已交付课程、可复用私有工程 |

时间来自原项目记录、说明书或实验材料；阶段时间不等于当前 Git 提交日期。

## 阅读入口

灵巧操作与机器人算法先看 **Super Hand → T1 → 轮毂抓取**；平台开发可看 **冶炼桌面程序 → 机器人舞蹈 → 视频工作台**；机械设计可看 **机械宠物 → 分拣机械臂 → 太阳能小车**。

## 仓库关系

| 研发仓库 | 展示 / 公开入口 |
|---|---|
| Robotcup-super-hand | 当前技术展示 super-hand-showcase；dexhand-calligraphy 为较早程序 |
| Robot-Dance | robot-motion-platform |
| 26DigitalInfrastructure 的 liu-qi 工作 | robocup-t1-control-lab |
| mechanical-pet-design-records | 完整设计版本与 Release 私有归档；modular-robot-pet 为公开设计概览与历史自有程序 |
| automotive-wheel-embodied-intelligence | 研发快照私有；本页公开任务和结果摘要 |
| teaching-video-workbench | 可复用源码和课程 Release 私有；本页公开效果与方法 |
| dexrobot_mujoco / dexrobot_isaac / dexrobot_urdf | 上游依赖 fork，单独说明来源 |

原始工业数据、权重、设备标定、个人证明和不适合公开的研发资产未随本页公开。验证范围见 [记录](VALIDATION.md)。
