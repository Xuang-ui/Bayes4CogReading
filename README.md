# Bayes4Cog

以 Griffiths、Chater 与 Tenenbaum（2024）《Bayesian Models of Cognition》为主线，系统整理认知科学中的概率表征、贝叶斯推断、近似算法与领域模型，并配套可复现代码。

## 项目结构

```text
Bayes4Cog/
├── chapters/       # 按全书 22 章组织的笔记与代码
├── shared/         # 跨章节复用的数据、工具和图表
├── synthesis/      # 方法矩阵、跨章比较与最终综合
└── Griffiths et al. - 2024 - Bayesian models of cognition reverse engineering the mind.pdf
```

每个章节目录包含：

- `notes.md`：核心问题、模型、推导、认知主张和批判性笔记。
- `code/`：该章模型复现、模拟、诊断与测试。

## 建议工作流

1. 阅读前先在 `notes.md` 写下本章问题和预期。
2. 将模型拆成表征、生成过程、先验、似然、推断和行为映射。
3. 优先实现小规模精确版本，再实现近似或概率编程版本。
4. 做参数恢复、模型恢复和后验预测检查。
5. 将跨章节结论汇总到 `synthesis/`。

章节索引见 [chapters/README.md](chapters/README.md)。
