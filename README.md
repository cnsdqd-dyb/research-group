# Research Projects

浙江大学 Hehe Fan（范鹤鹤）课题组的公开研究项目索引。

导师：[个人主页](https://hehefan.github.io/) · [论文列表](https://hehefan.github.io/publications/)

本页为初始项目索引，包含导师代表性工作，不代表完整组内成果。研究方向依据导师主页；正式组名暂未确定。各项目由原仓库维护，本仓库仅汇总公开论文、项目及数据资源。

**方向导航：** [Computer Vision](#computer-vision) · [LLMs & Agents](#llms--agents) · [Embodied AI](#embodied-ai) · [AI for Science](#ai-for-science)

## Computer Vision

| 项目 | 一句话简介 | 方向标签 | 年份／会议 | 资源与发布状态 |
| --- | --- | --- | --- | --- |
| Hi-Lo Prune | 通过分层视觉 token 选择和剪枝前的信息融合降低视觉语言模型推理开销。 | Computer Vision · Efficient VLMs · Token Pruning | CVPR 2026 | [论文](https://openaccess.thecvf.com/content/CVPR2026/html/Sun_Hi-Lo_Prune_Look_at_What_Youll_Lose_before_Pruning_with_CVPR_2026_paper.html) · [仓库入口](https://github.com/sealost/Hi-Lo_Prune)；当前仅有 README，尚无实现代码。 |
| P4Transformer | 结合四维点卷积与 Transformer 建模点云视频中的空间结构和运动信息。 | Computer Vision · Point Clouds · 4D Perception | CVPR 2021 Oral | [代码](https://github.com/hehefan/P4Transformer) |
| PSTNet | 通过时空卷积学习点云序列的空间几何和时间变化。 | Computer Vision · Point Clouds · Spatio-temporal Learning | ICLR 2021 | [论文](https://openreview.net/forum?id=O3bqkf_Puys) · [代码](https://github.com/hehefan/Point-Spatio-Temporal-Convolution) |

跨方向项目：[PointListNet](#ai-for-science) 将三维点列表建模用于蛋白质任务。

## LLMs & Agents

| 项目 | 一句话简介 | 方向标签 | 年份／会议 | 资源与发布状态 |
| --- | --- | --- | --- | --- |
| Structured Reasoning | 用显式推理步骤标签与图结构优化研究语言模型推理的效率和可解释性。 | LLMs & Agents · Reasoning · Post-training | ICLR 2026；早期预印本 2025 | [正式论文](https://proceedings.iclr.cc/paper_files/paper/2026/hash/ad5b3f324b24c17cdc2f3712298c76bd-Abstract-Conference.html) · [早期预印本](https://arxiv.org/abs/2506.20241) · [项目仓库](https://github.com/cnsdqd-dyb/Enhancing-Large-Language-Models-through-Structured-Reasoning) · [数据](https://huggingface.co/datasets/FreeFrank/Structured-Reasoning)；训练代码和检查点尚未发布。 |
| Super Research | 为需要深度调查、广泛检索与证据综合的复杂研究问题构建任务与评测基准。 | LLMs & Agents · Deep Research · Benchmark | arXiv 2026；未核实会议录用信息 | [论文](https://arxiv.org/abs/2603.00582) · [项目与榜单](https://cnsdqd-dyb.github.io/Super-Research-Benchmark/) |
| VillagerAgent | 在 Minecraft 中使用任务依赖图协调多个智能体执行复杂任务。 | LLMs & Agents · Multi-Agent · Planning | Findings of ACL 2024 | [论文](https://aclanthology.org/2024.findings-acl.964/) · [代码](https://github.com/cnsdqd-dyb/VillagerAgent-Minecraft-multiagent-framework) |

Structured Reasoning 的正式论文题名为 *Structured Reasoning for LLMs: A Unified Framework for Efficiency and Explainability*；早期预印本题名为 *Enhancing Large Language Models through Structured Reasoning*。会议信息以正式论文集为准。

## Embodied AI

No public projects are currently indexed in this direction.

## AI for Science

| 项目 | 一句话简介 | 方向标签 | 年份／会议 | 资源与发布状态 |
| --- | --- | --- | --- | --- |
| CDConv | 通过连续与离散卷积联合建模蛋白质的三维几何和序列结构。 | AI for Science · Protein Modeling | ICLR 2023 | [论文](https://openreview.net/forum?id=P5Z-Zl9XJ7) · [代码](https://github.com/hehefan/Continuous-Discrete-Convolution) |
| PointListNet | 以 Transformer 风格网络联合建模三维点列表的几何与顺序结构，并应用于蛋白质任务。 | AI for Science · Computer Vision · Protein Modeling · Transformers | CVPR 2023 | [论文](https://openaccess.thecvf.com/content/CVPR2023/html/Fan_PointListNet_Deep_Learning_on_3D_Point_Lists_CVPR_2023_paper.html)；未核实代码仓库。 |

## 补充项目与返回链接

通过 Issue 或 Pull Request 补充项目，格式与核实要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。

项目维护者可在各自 README 中加入以下返回链接：

```markdown
[课题组项目索引](https://github.com/cnsdqd-dyb/research-group)
```

此处仅提供示例。修改其他项目仓库前，需先列出仓库、插入位置和具体改动，并取得仓库维护者及本入口负责人的批准。

公开资源核对日期：2026-10-09。资源状态可能随各项目的后续发布而变化。
