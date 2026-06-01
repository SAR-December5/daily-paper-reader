---
title: Bayesian optimisation and graph-based rheology enable sequence-dependent modelling of DNA materials
title_zh: 贝叶斯优化与基于图的流变学实现DNA材料的序列依赖建模
authors: "Gadzekpo, A., Hilbert, L."
date: 2026-05-30
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.27.728076v1.full.pdf"
tags: ["query:ai-design"]
score: 8.0
evidence: 使用贝叶斯优化和机器学习进行DNA材料设计优化
tldr: DNA材料设计面临分子与宏观性质的尺度差异及设计空间庞大。提出机器学习流程：用贝叶斯优化参数化序列感知粗粒度模拟，以图基流变学评估流变性质。以DNA纳米星为例，核苷酸级模拟优化珠-弹簧模型，引入流体动力学，预测与实验吻合。该方法桥接尺度并自动化粗粒度化，实现基于序列-性质关系的定向设计。
source: biorxiv
selection_source: fresh_fetch
motivation: 解决DNA材料从序列到流变性质的跨尺度设计与手动探索难题。
method: 组合贝叶斯优化与图基流变学，参数化并评估序列感知的粗粒度DNA模拟。
result: 以DNA纳米星验证，优化模型预测与实验一致，且泛化至理论图表示。
conclusion: 机器学习桥接尺度并自动化粗粒度化，实现DNA材料序列-性质关系的定向设计。
---

## 摘要
连接分子和涌现特性对于设计软物质至关重要。合成DNA材料因其序列设计空间支持广泛的材料特性而具有吸引力。DNA材料的目标设计受限于尺度差异和手动探索庞大设计空间。我们通过一个计算工作流程解决这一挑战，该工作流程将序列级设计与流变材料特性联系起来。具体地，我们使用机器学习参数化可扩展的、DNA序列感知的模拟，然后使用基于图的流变学评估它们。在我们的示例中，我们研究由单链组装的自相互作用、多价DNA纳米星组成的材料。纳米星的结构和柔性通过核苷酸级oxDNA模拟量化，实现了更粗粒度的珠-弹簧模型的贝叶斯优化。珠-弹簧模型允许有效模拟纳米星之间的网络形成，受杂交自由能控制，这些自由能通过oxDNA和NUPACK计算。纳米星价态和网络连通性通过基于图的方法转化为流变材料特性，我们将其扩展以包括流体动力学相互作用，与实验参考数据良好一致。我们通过分析DNA材料的理论图表示来推广我们的发现，并展示机器学习如何优化序列亲和性以产生所需的流变响应。我们的工作说明了机器学习如何桥接尺度并自动化粗粒化，以通过序列-属性关系促进DNA材料的目标设计。

## Abstract
Bridging molecular and emergent properties is essential for designing soft matter. Synthetic DNA materials are attractive in this context because their sequence design space supports a wide range of material properties. Targeted design of DNA materials is hindered by scale differences and manual exploration of vast design spaces. We address this challenge with a computational workflow that links sequence-level design to rheological material properties. Concretely, we use machine learning to parametrise scalable, DNA-sequence-aware simulations, which we then evaluate using graph-based rheology. In our example, we study materials composed of self-interacting, multivalent DNA nanostars assembled from single strands. Structure and flexibility of nanostars are quantified with nucleotide-level oxDNA simulations, enabling Bayesian optimisation of a more coarse-grained bead-spring model. The bead-spring model allows efficient simulation of network formation between nanostars, governed by hybridisation free energies, which are computed with oxDNA and NUPACK. Nanostar valency and network connectivity are translated into rheological material properties with a graph-based method that we extend to include hydrodynamic interactions, yielding good agreement with experimental reference data. We generalise our findings by analysing theoretical graph representations of DNA materials and show how machine learning can optimise sequence affinities to produce desired rheological responses. Our work illustrates how machine learning can bridge scales and automate coarse-graining to facilitate targeted design of DNA materials through sequence-property relationships.