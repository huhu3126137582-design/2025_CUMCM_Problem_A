# 2025 CUMCM Problem A

本仓库整理了 2025 年全国大学生数学建模竞赛 A 题的论文、MATLAB 源程序与结果文件。

## 仓库结构

```text
.
├── paper/      # 论文 PDF、LaTeX 源码、模板类文件及论文插图
├── code/       # MATLAB 主程序与辅助函数
└── results/    # 题目要求提交的结果表
```

## 论文

- `paper/国赛A题.pdf`：最终论文
- `paper/国赛A题.tex`：论文 LaTeX 源码
- `paper/cumcmthesis.cls`：CUMCM 论文模板类文件

如需重新编译论文，请在 `paper/` 目录下编译 `国赛A题.tex`。

## 代码

主程序位于 `code/` 目录：

- `wenti_1.m`：问题一
- `wenti_2.m`：问题二
- `wenti_3.m`：问题三
- `wenti_4.m`：问题四
- `wenti_5.m`：问题五

其余 `.m` 文件为辅助函数。运行时建议将 MATLAB 当前工作目录切换到 `code/`，再运行对应主程序。

## 结果

- `results/result1.xlsx`：问题三结果
- `results/result2.xlsx`：问题四结果
- `results/result3.xlsx`：问题五结果

## 方法概述

论文围绕烟幕干扰弹投放策略建立运动学模型、遮蔽判据和优化模型，主要使用粒子群优化算法、PSO-DE 融合算法、二分法与匈牙利算法完成求解。
