<h1 align="center">Agentic CAD: A Survey</h1>

<p align="center">
  A systematic survey of <b>modern Agentic CAD</b>, centered on state-dependent interaction between foundation-model agents and CAD/engineering environments.
</p>

<p align="center">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898">
    <img src="https://img.shields.io/badge/Paper-SSRN-blue" alt="SSRN">
  </a>
  <a href="#citation">
    <img src="https://img.shields.io/badge/Citation-BibTeX-orange" alt="Citation">
  </a>
  <a href="./pdf_中文翻译.zip">
    <img src="https://img.shields.io/badge/Chinese-Translations-red" alt="Chinese Translations">
  </a>
</p>

---

## Overview

We define **modern Agentic CAD** as foundation-model-driven systems that make sequential CAD-related decisions conditioned on evolving user, model, geometric, or engineering states.

The survey takes **state-dependent agent-CAD interaction** as the primary unit of analysis. It organizes the literature through a **workflow taxonomy**—specify, plan, act, observe, verify, and recover—and a complementary **task taxonomy** covering objectives across the CAD lifecycle. We further review model and interaction foundations, learning and experience accumulation, evaluation, and open research challenges.

📄 **Paper:** [Agentic CAD: A Survey — SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898)

<p align="center">
  <img src="./assets/1.png" width="95%" alt="Conceptual overview of modern Agentic CAD">
</p>

<p align="center">
  <em>Figure 1. Conceptual overview of modern Agentic CAD and the two organizing views adopted in this survey.</em>
</p>

---

## CAD Agent Learning

We analyze CAD agent learning through three related dimensions: **action granularity**, **reward granularity**, and **credit-assignment granularity**, spanning one-shot program-level learning, multi-turn program-agent learning, and step-level CAD-agent learning.

<p align="center">
  <img src="./assets/2.png" width="95%" alt="Action, reward, and credit granularity in CAD agent learning">
</p>

<p align="center">
  <em>Figure 2. Action, reward, and credit granularity in CAD agent learning.</em>
</p>

---

## Evaluation

We extend evaluation beyond final-product quality to a multidimensional view covering **CAD correctness**, **agent trajectory**, **reliability**, and **resource cost**, while explicitly considering whether the evaluator is appropriate for the property being assessed.

<p align="center">
  <img src="./assets/3.png" width="95%" alt="Multidimensional evaluation framework for Agentic CAD">
</p>

<p align="center">
  <em>Figure 3. A multidimensional evaluation framework for Agentic CAD.</em>
</p>

---

## Resources

- 📄 [**Paper on SSRN**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898)
- 🇨🇳 [**Chinese Translation Resources**](./pdf_中文翻译.zip)

---

## Citation

If you find this survey or repository useful, please consider citing:

```bibtex
@misc{zhang2026agenticcad,
  title        = {Agentic CAD: A Survey},
  author       = {Zhang, Xuecheng and He, Fazhi and Zhou, Xiaolu and Deng, Enxi
                  and Qu, GuanLin and Wang, Haokun and Lin, Qingyuan
                  and Fan, Rubin and Lei, Yixiang and Wan, Ruibo},
  year         = {2026},
  howpublished = {SSRN},
  url          = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7524898}
}
```

---

## Contributing

Suggestions, corrections, and new papers related to **Agentic CAD** are welcome via issues or pull requests.
