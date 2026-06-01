---
title: Objective curriculum-guided design of multi-property proteins
title_zh: 多特性蛋白质的目标课程引导设计
authors: "Liu, L., Zhao, J., Xie, X., Xu, S., Ren, M., Zhang, X., He, Z., Liu, F., Yu, C., Wang, K., Wang, X., Liang, X., Ye, X., Bu, D., Zhou, H."
date: 2026-05-29
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.25.727596v2.full.pdf"
tags: ["query:ai-design"]
score: 8.0
evidence: 使用AI进行课程指导的多属性蛋白质设计
tldr: 多属性蛋白质设计面临性质间相互依赖甚至冲突的挑战，现有一次性联合优化方法筛选效率低。本文提出OCDesign框架，基于目标课程原则，逐步引入溶解度、结构一致性、结合亲和力和耐碱性等目标。在蛋白A模型上，课程式方法相比一次性优化显著减少湿实验次数，成功设计出兼具多种期望属性的蛋白质。该工作表明目标顺序是高维设计空间中可及性的关键决定因素。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有一次性多目标蛋白质优化方法成功率低、筛选成本高，需要更高效的设计策略。
method: 提出OCDesign框架，按课程顺序逐步引入目标，结合计算机生成、Pareto最优选择和湿实验验证。
result: 在抗体结合蛋白A上，课程式设计成功获得同时满足溶解度、结构一致性、结合亲和力和耐碱性的蛋白质，实验次数大幅减少。
conclusion: 目标课程式设计是一种实用的多属性蛋白质设计策略，目标顺序决定高维设计空间的可及性。
---

## 摘要
设计同时具备多种生化特性的功能性蛋白质仍然是一个重大挑战，因为关键的蛋白质特性（如溶解度、稳定性、结合亲和力和耐化学性）往往相互依赖甚至相互冲突。当前的方法通常试图一次性联合优化多个功能目标，然后通过大量筛选来识别罕见的可行设计。在此，我们引入了OCDesign，这是一个用于多特性蛋白质设计的目标课程引导框架。OCDesign基于目标课程原则，即目标引入的顺序会影响功能解决方案的可及性。在OCDesign的每一轮设计中，候选序列通过计算机模拟生成，跨多个特性进行评估，基于帕累托最优权衡进行选择，并进行实验验证，每个实验阶段测试课程中新引入目标的作用。以抗体结合蛋白A为模型系统，我们表明一次性优化无法产生功能性设计，而分阶段课程——从溶解度和结构一致性进展到结合亲和力，再到耐碱性——能够通过显著减少湿实验来设计具有多种所需特性的蛋白质。这些结果确立了OCDesign作为一种实用的计算-实验策略，用于组织和整合蛋白质设计中的多个目标，并表明目标排序是高维设计空间中可及性的关键决定因素。

## Abstract
Designing functional proteins that simultaneously possess multiple biochemical properties remains a significant challenge, as key protein properties, such as solubility, stability, binding affinity, and chemical resistance, are often interdependent or even conflicting. Current approaches typically attempt to jointly optimize multiple functional objectives in one shot, followed by extensive screening to identify rare feasible designs. Here, we introduce OCDesign, an objective curriculum-guided framework for multi-property protein design. OCDesign is based on the objective curriculum principle, which states that the order in which objectives are introduced can shape the accessibility of functional solutions. In each design round of OCDesign, candidate sequences are generated in silico, assessed across multiple properties, selected based on Pareto-optimal trade-offs, and experimentally validated, with each experimental stage testing the role of the newly introduced objective within the curriculum. Using antibody-binding protein A as a model system, we show that one-shot optimization fails to yield functional designs, whereas a staged curriculum--progressing from solubility and structural consistency to binding affinity, and then to alkaline resistance--enables the design of proteins possessing multiple desired properties through substantially fewer wet-lab experiments. These results establish OCDesign as a practical computational-experimental strategy for organizing and integrating multiple objectives in protein design, and suggest that objective ordering is a key determinant of accessibility in high-dimensional design spaces.