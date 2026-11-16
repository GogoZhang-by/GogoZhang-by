<div align="center">

# 张博洋 · Zhang Boyang

**量化决策建模方向 · 计算机科学本科生**

上海科技大学（ShanghaiTech University） · 计算机科学与技术（Computer Science）

[![Email](https://img.shields.io/badge/Email-jingwuxueyun%40qq.com-0e7c66?style=flat-square&logo=maildotru&logoColor=white)](mailto:jingwuxueyun@qq.com)
[![GitHub](https://img.shields.io/badge/GitHub-GogoZhang--by-181717?style=flat-square&logo=github)](https://github.com/GogoZhang-by)
[![Gitee](https://img.shields.io/badge/Gitee-by__Zhang__haha-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/by_Zhang_haha)

</div>

## 关于我

上海科技大学计算机科学与技术专业本科生（2025 级），主攻量化交易、信贷风控、反欺诈等金融科技方向与数智供应链决策，技术栈覆盖 Python/C/C++ 与 SQL，熟悉 XGBoost、Git、Docker、WSL。正在通过竞赛与项目积累量化建模与工程落地经验。

## 技术栈


**语言** `Python` `C` `C++` `SQL` 


**框架** `LightGBM` `XGBoost` `PyTorch` `Pandas` 


**工具** `Git` `Docker` `WSL` 


**方向** `量化交易` `信贷风控` `反欺诈` `数智供应链` 





## 精选项目


### 沪深300 截面选股与冠军方案复刻

参加上海科技大学首届量化金融挑战赛（DataTech 社团 × TopK AI 量化实验室联合主办），以沪深 300 指数次日 open-to-open 收益的截面 RankIC 为评测口径，构建截面选股模型，并完整复刻冠军 FNR 方案做工程化改进。

- 构建 71 维特征（49 基线因子 + 12 时序扩展 + 11 截面均值 + Barra 风格因子）的 LightGBM 截面排序模型，诚实 OOS（无早停泄露）主窗 RankIC 0.0508、IR 1.734
- 完整复刻冠军 FNR（Factor Neighborhood Ranker）方案：347 维 mixed61 特征、LightGBM+TabM 集成底座、截面自注意力教师、kNN 邻域头与尾部重排，并完成 Windows/跨平台工程适配
- 建立双窗口 OOS 验证门槛（主窗 RankIC 增益≥0.003 且 IR 不降），隔离验证 5 条冠军技巧并定位失败根因，全部否决以规避过拟合
- 工程完整性：README / 单元测试 / requirements / LICENSE 齐备，CPU 单机可复现，对引用的冠军代码保留归属声明

`Python` `LightGBM` `PyTorch` `NumPy` `Pandas` `TabM` 

[查看代码 →](https://github.com/GogoZhang-by/csi300-challenge-2026)

> 基线 OOS 主窗 RankIC 0.0508 / IR 1.734；副窗 RankIC 0.0441 / IR 2.144








## 教育背景


- **上海科技大学（ShanghaiTech University）** · 计算机科学与技术（Computer Science） · 工学学士（在读）（2025-09 – 预计 2029-06）



## 联系方式

- 邮箱：jingwuxueyun@qq.com

- GitHub：https://github.com/GogoZhang-by

- Gitee：https://gitee.com/by_Zhang_haha



---

<sub>本页由 profile.yaml 自动生成 · 最后更新 2026-11-16</sub>
> （注：部分内容由豆包 AI 生成）