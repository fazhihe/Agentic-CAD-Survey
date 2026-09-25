# Agentic CAD: A Survey

**A survey of Agentic CAD, CAD agents, and foundation-model-driven CAD systems.**

<p align="center">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898">
    <img src="https://img.shields.io/badge/Paper-SSRN-blue" alt="SSRN">
  </a>
  <a href="#citation">
    <img src="https://img.shields.io/badge/Citation-BibTeX-orange" alt="Citation">
  </a>
  <a href="./pdf_中文翻译/">
    <img src="https://img.shields.io/badge/Resources-Chinese%20Translations-red" alt="Chinese Translations">
  </a>
</p>

---

## Overview

Recent advances in large language models and multimodal foundation models are transforming computer-aided design (CAD) from one-shot generation toward increasingly **agentic** workflows.

This survey studies **Agentic CAD** as systems in which foundation models participate in iterative decision-making and interact with CAD environments through processes such as design intent understanding, planning, tool use, execution, observation, verification, and feedback.

We organize the emerging literature around the **agent–CAD interaction loop**, CAD task categories, agent learning, and evaluation.

📄 **Paper:** [Agentic CAD: A Survey — SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898)

<br>

<p align="center">
  <img src="./assets/1.png" width="95%" alt="Overview of Agentic CAD">
</p>

<p align="center">
  <em>Modern Agentic CAD: state-dependent interaction across the CAD lifecycle.</em>
</p>

---

## Agent Learning

A central question in Agentic CAD is how an agent learns from interaction with CAD environments.

We examine learning paradigms at different levels of granularity, including **one-shot program-level learning**, **multi-turn program-level learning**, and **step-level CAD agent learning**, together with different strategies for reward design and credit assignment.

<p align="center">
  <img src="./assets/2.png" width="95%" alt="Agent Learning in Agentic CAD">
</p>

<p align="center">
  <em>Action, reward, and credit granularity in CAD agent learning.</em>
</p>

---

## Evaluation

Evaluating Agentic CAD requires more than measuring whether a final CAD model is geometrically correct.

We discuss a multidimensional evaluation framework covering **CAD correctness**, **agent trajectories**, **reliability**, **resource cost**, and **evaluator validity**, enabling analysis of both final outcomes and the reasoning-and-action process that produces them.

<p align="center">
  <img src="./assets/3.png" width="95%" alt="Evaluation Framework for Agentic CAD">
</p>

<p align="center">
  <em>A multidimensional evaluation framework for Agentic CAD.</em>
</p>

---

## Resources

- 📄 [**Survey Paper on SSRN**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898)
- 🇨🇳 [**Chinese Translation Resources**](./pdf_中文翻译/)
- 📁 Supplementary materials and figures are maintained in this repository.

---

## Citation

If you find this survey or repository useful, please consider citing:

```bibtex
@misc{zhang2026agenticcad,
  title        = {Agentic CAD: A Survey},
  author       = {Zhang, Xuecheng and He, Fazhi and Zhou, Xiaolu and Deng, Enxi
                  and Qu, Guanlin and Wang, Haokun and Lin, Qingyuan
                  and Fan, Rubin and Lei, Yixiang and Wan, Ruibo},
  year         = {2026},
  month        = sep,
  howpublished = {SSRN},
  url          = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898}
}
```

---

## Contributing

Suggestions, corrections, and new papers related to **Agentic CAD** are welcome.

Please feel free to open an issue or submit a pull request.
