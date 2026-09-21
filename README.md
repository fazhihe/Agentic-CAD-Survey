# Agentic CAD: A Survey

**A continuously maintained literature corpus for Agentic CAD, CAD Agents, and foundation-model-driven CAD systems.**

[中文说明](#中文说明) · [Survey](#survey) · [Corpus](#reference-corpus) · [Download](#download) · [Citation](#citation)

---

## Overview

This repository accompanies our survey:

> **Agentic CAD: A Survey**

The survey studies the emerging field of **Agentic CAD**, with particular emphasis on foundation-model-driven systems that make sequential and state-dependent decisions in CAD-related workflows.

Rather than treating CAD intelligence only as an input-to-output generation problem, we focus on the interaction loop between agents and CAD environments: how an agent understands design intent, plans, acts, observes the evolving CAD state, verifies the result, and recovers from errors.

The survey organizes existing research from two complementary perspectives:

**Workflow taxonomy:** intent and specification; planning and orchestration; action selection and tool use; execution, observation, and runtime state; verification and feedback; recovery and control.

**Task taxonomy:** conceptual design; part generation; reconstruction and reverse engineering; CAD editing, review, and engineering documentation; assembly and articulated design; CAD–CAE analysis and design optimization; and design for manufacturing.

---

## Reference Corpus

This repository provides the literature corpus collected and organized during the preparation of the survey.

The literature cutoff of the current survey manuscript is **August 21, 2026**.

For literature published from 2024 onward, the initial candidate set contained 86 records. After topical screening, 71 records were retained, including:

| Year | Retained records |
| ---- | ---------------: |
| 2024 |                4 |
| 2025 |               25 |
| 2026 |               42 |

Additional literature was collected for core analysis, supporting evidence, historical context, CAD representations, learning-based CAD generation, and related agent research.

The corpus covers several categories used in the survey:

| Category                             | Description                                                                                                                    |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| Core modern Agentic CAD              | Foundation-model-driven systems with CAD-related actionability and sequential state-dependent control                          |
| Adjacent agentic / assistive methods | Methods supporting validation, state representation, diagnosis, recovery, benchmarking, or other components of the agent loop  |
| Generative CAD foundations           | CAD generation methods and representations that provide foundations for later CAD agents                                       |
| Historical CAD agents                | Earlier rule-based, knowledge-based, multi-agent, and learned CAD-agent systems                                                |
| Supporting literature                | General agent, CAD representation, reinforcement learning, engineering, CAD/CAE/CAM, and related references used in the survey |

The corpus will be continuously updated as new Agentic CAD research becomes available.

---

## Download

Because the complete bilingual PDF corpus is large, PDF files are distributed through **GitHub Releases** rather than stored directly in the Git repository.

### Corpus packages

**English papers**

Download the latest English PDF corpus from:

**Releases → `agentic-cad-corpus-en-v1.0.zip`**

**中文文献**

中文 PDF 语料可从 Releases 下载：

**Releases → `agentic-cad-corpus-zh-v1.0.zip`**

The repository itself contains lightweight and version-controlled research resources such as bibliographic records, metadata, and the survey manuscript.

---

## Corpus Organization

We recommend organizing the downloaded corpus as follows:

```text
agentic-cad-corpus/
├── en/
│   ├── core_agentic_cad/
│   ├── adjacent_methods/
│   ├── generative_foundations/
│   ├── historical_agents/
│   └── supporting_literature/
│
└── zh/
    ├── core_agentic_cad/
    ├── adjacent_methods/
    ├── generative_foundations/
    ├── historical_agents/
    └── supporting_literature/
```

Each paper should share the same identifier across the English and Chinese collections whenever a corresponding bilingual version is available.

For example:

```text
en/core_agentic_cad/025_TOOLCAD.pdf
zh/core_agentic_cad/025_TOOLCAD_zh.pdf
```

---

## Metadata

Machine-readable bibliographic metadata are provided in:

```text
metadata/papers.csv
```

Recommended fields include:

| Field         | Description                        |
| ------------- | ---------------------------------- |
| `id`          | Unique corpus identifier           |
| `title`       | Paper title                        |
| `authors`     | Authors                            |
| `year`        | Publication year                   |
| `category`    | Survey corpus category             |
| `task`        | CAD task category                  |
| `workflow`    | Relevant agent workflow components |
| `venue`       | Journal, conference, or preprint   |
| `status`      | Peer-reviewed / preprint           |
| `doi`         | DOI                                |
| `arxiv`       | arXiv identifier                   |
| `project_url` | Project or repository URL          |
| `pdf_en`      | English PDF availability           |
| `pdf_zh`      | Chinese PDF availability           |
| `license`     | Source publication license         |
| `notes`       | Additional annotations             |

The BibTeX bibliography used by the survey is available in:

```text
bibliography/agentic_cad.bib
```

---

## Chinese Translations

Chinese translations are provided to facilitate literature reading and academic research.

Unless explicitly stated otherwise, translated versions should be considered **unofficial research translations**. Readers should refer to the original publication when checking technical terminology, equations, experimental results, or claims, and should cite the original paper rather than the translated PDF.

Only materials for which redistribution and, where applicable, derivative/translation rights permit publication should be distributed through this repository.

---

## Copyright and Redistribution

Copyright of the original publications belongs to their respective authors and/or publishers.

This repository does **not** claim ownership of third-party publications and does not relicense the original papers.

PDF copies are included only when their licenses or permissions allow redistribution. For papers that cannot legally be redistributed, the corpus should provide bibliographic metadata together with links to the official publisher page, DOI, arXiv page, author manuscript, or other authorized source instead of hosting the PDF directly.

The license of the documentation, metadata, annotations, and other original materials in this repository is specified separately in the repository `LICENSE` file.

---

## Survey

The latest survey manuscript is available at:

```text
paper/Agentic_CAD_A_Survey.pdf
```

The survey discusses:

Agentic CAD definitions and scope; the evolution from classical CAD agents to modern foundation-model-driven agents; workflow and task taxonomies; model representation and operability; topology selection and persistent references; editability and runtime state; cross-backend CAD; reinforcement learning, knowledge, memory, and skill acquisition; evaluation; challenges; and future research directions.

---

## Citation

If this survey or corpus is useful for your research, please cite:

```text
Xuecheng Zhang, Fazhi He, Xiaolu Zhou, GuanLin Qu, Haokun Wang,
Qingyuan Lin, Rubin Fan, Yixiang Lei, and Ruibo Wan.
"Agentic CAD: A Survey." Preprint, 2026.
```

BibTeX:

```bibtex
@article{zhang2026agenticcad,
  title   = {Agentic CAD: A Survey},
  author  = {Zhang, Xuecheng and He, Fazhi and Zhou, Xiaolu and
             Qu, GuanLin and Wang, Haokun and Lin, Qingyuan and
             Fan, Rubin and Lei, Yixiang and Wan, Ruibo},
  year    = {2026},
  note    = {Preprint}
}
```

The citation information will be updated after an official arXiv, conference, journal, or DOI record becomes available.

---

## Contributing

Agentic CAD is developing rapidly, and we welcome suggestions for newly released papers, missing references, metadata corrections, and classification corrections.

When suggesting a paper, please provide its title, authors, year, DOI or arXiv link, publication status, and a short explanation of its relevance to Agentic CAD.

Issues and pull requests are welcome.

---

## 中文说明

本仓库是综述 **《Agentic CAD: A Survey》** 的配套开源文献语料库。

本综述关注由大语言模型、视觉语言模型及其他基础模型驱动的 CAD Agent，重点研究 Agent 如何根据不断变化的用户需求、CAD 模型状态、几何信息以及工程分析结果进行连续决策。

与仅研究一次性 CAD 生成不同，本综述更加关注 Agent 与 CAD 环境之间的闭环交互过程，包括需求理解、规划、工具调用、执行、状态观测、验证、反馈以及错误恢复。

仓库将持续维护 Agentic CAD 相关论文、参考文献元数据、BibTeX 以及在版权许可范围内可以公开分发的中英文 PDF 资源。

由于完整 PDF 语料体积较大，PDF 数据集通过 **GitHub Releases** 提供下载，Git 仓库本身仅保存综述、文献目录和轻量级元数据。

如果发现遗漏的新论文、错误的分类或文献信息，欢迎提交 Issue 或 Pull Request。

---

## Disclaimer

This repository is intended for academic research and literature organization.

Inclusion of a paper in the corpus does not imply endorsement of its claims or conclusions.

For authoritative content, citation information, and licensing terms, please refer to the original publication.
