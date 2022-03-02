# porj120-anomaly-detection-for-os
实现智能的操作系统异常检测  

## 项目描述

操作系统智能运维能提供精准的业务质量感知、支撑用户体验优化、全面提升运维服务质量。当操作系统发生异常时（如：内存泄漏、网络丢包、CPU冲高等），需要快速发现异常的进程。本项目旨在实现进程粒度的数据采集（如eBPF、Sysdig等工具，采集数据包括系统调用、cpu、内存、网络等资源实时占用等），结合现有的机器学习算法（如时间序列异常检测、日志分析等），实现快速准确的异常检测。其难点在两方面：1.针对不同类型的异常，如何选取重要特征和异常检测算法；2.不同场景和应用负载时，异常模式存在差异，如何做到框架和算法的通用性。

## 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生（2022年春季学期或之后毕业的本科生及研究生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

- gitee @gaoruoshu
- email gaoruoshu@huawei.com

## 难度

较大（可提供额外指导和参考材料）

## 特征

- 实现系统调用、进程实时占用资源（cpu、内存、网络）的采集
- 针对特定类型的异常，提供一套分析方案和实现


## 进阶特性

- 集成多种异常检测算法，针对不同场景下的数据，自动选择最优算法和参数
- 算法框架具备通用性，适用于不同的操作系统

## License

任意开源license都可

## 预期目标

特征中的要求为必备能力，进阶特性为建议内容，不要求一定完成。选择本项目的同学也可提出自己的新想法，得到导师任何支持后亦可加入预期目标或进阶特性。 
