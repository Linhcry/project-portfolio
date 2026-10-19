# 刘琦的项目档案

方向：**机器人 / 控制 / 算法**。这里按项目资料时间整理已公开的代码、机械设计和研究记录，供简历读者查看具体实现与验证程度。

## 项目时间线

| 时间依据 | 项目 | 主要工作与产出 | 当前证据 |
|---|---|---|---|
| 本科期间 · 2024 年归档线索 | [太阳能小车机构与传动设计](https://github.com/Linhcry/solar-car-mechanical-design) | 主要负责整车方案、结构建模与参数匹配；保留车身迭代、凸轮机构与带公式的计算表。 | CAD 和计算资料 |
| 2026-04 | [PVC 凝胶仿生鱼尾](docs/pvc-fish-tail.md) | 本科团队项目的柔性驱动技术路线与汇报材料整理。 | 团队项目简介 |
| 2026-05—06 | [快递分拣机器人机械臂](https://github.com/Linhcry/parcel-sorting-arm-design) | 本科毕设：机械结构、伺服与传动选型、轴系校核和静力有限元分析。 | 设计与历史仿真 |
| 2026-07 起 | [RoboCup T1 控制与强化学习](https://github.com/Linhcry/robocup-t1-control-lab) | 23 DoF 机器人运动控制、步态接入、PPO 实验与起身任务评测。 | 仿真研发 |
| 2026-08 起 | [机器人舞蹈动作平台](https://github.com/Linhcry/robot-motion-platform) | 视频动捕、动作重定向、分阶段任务编排、运动诊断和多视图同步。 | 平台与算法适配 |
| 2026-09 起 | [模块化机器人机械设计](https://github.com/Linhcry/modular-robot-pet) | SolidWorks 自动建模、模块接口、储物舱锁止、相机托架和载荷筛选。 | 设计候选与工程校核 |
| 2026-09 起 | [五指灵巧手书写仿真](https://github.com/Linhcry/dexhand-calligraphy) | 题目识别、笔画规划、机械臂 IK、抓笔与接触反馈、书写质量评估。 | 仿真程序与测试 |
| 2026-09 | [无人机应急运输联合优化](https://github.com/Linhcry/uav-disaster-optimization) | 异构无人机分配、路径定价、电池充电、通信约束和独立方案验证。 | 算法与建模程序 |
| 2026-10 起 | [冶炼过程视觉与在线分析平台](https://github.com/Linhcry/smelter-analytics-platform) | 整合终点判别、铁含量回归、图像数据管理、训练评估与过程回放。 | 可运行平台；现场验收待数据 |

时间来自原项目 Git 记录、说明书或实验/设计记录；只知道阶段的条目按月份标注。本科小车日期来自归档材料，具体赛事时间仍可补充。代码现在整理上传，提交日期采用实际日期。

## 建议阅读顺序

算法与控制岗位先看 **T1 控制 → 灵巧手 → 无人机优化**；机器人平台岗位可看 **舞蹈动作平台 → 冶炼分析平台**；机电岗位可看 **分拣机械臂 → 太阳能小车 → 模块化机器人**。每个仓库说明问题、程序入口、实际产出和验证范围。

## 与原 GitHub 仓库的关系

| 原仓库 | 来源与用途 |
|---|---|
| 26DigitalInfrastructure | 培训仓库 fork；个人工作在 liu-qi，公开代码已单独归档到 T1 控制项目 |
| Robot-Dance | 原舞蹈研发仓库，继续保留原有可见性；公开平台代码在 robot-motion-platform |
| Robotcup-super-hand | 原灵巧手研发仓库，继续保留原有可见性；公开程序在 dexhand-calligraphy |
| coff-Dream | 咖啡管理项目 fork，作为网页构建与工程组织参考 |
| dexrobot_mujoco / dexrobot_isaac / dexrobot_urdf | DexRobot 上游依赖 fork，模型与仿真基础，不作为个人原创算法项目 |

小说、低完成度小样例、安装包、个人证明材料和原始工业数据没有加入这组公开项目。完整研发工作区和原有私有仓库继续保留。

本次源码整理的测试范围见 [验证记录](VALIDATION.md)。
