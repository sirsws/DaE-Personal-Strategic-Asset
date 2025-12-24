# Reducing Alignment Debt in AI Advisory: The Dialogue-as-Elicitation (DaE) Framework

[**中文**](./README_CN.md) | **English**

![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## Abstract

In the emerging market of AI advisory services, a fundamental Principal-Agent Problem exists between users and AI agents. Users suffer from "sticky information," making it expensive to transfer tacit preferences via ad-hoc prompting. This friction results in "Alignment Debt." We propose Dialogue-as-Elicitation (DaE), a mechanism that shifts alignment from ex-post correction to ex-ante elicitation. DaE employs a dual-agent architecture to construct a "Personal Strategic Asset"—a structured, reusable ledger of user attributes.

## Repository Contents

*   `src/dae_minimal_prompt.txt`: The operational minimal prompt for the Elicitation and Application agents.
*   `papers/`:
    *   `dae_ssrn.pdf`: **SSRN Version** (Focus: Management, Alignment Debt, & Economic Mechanism).
    *   `dae_arxiv_draft.pdf`: **ArXiv Draft** (Focus: Technical Implementation & Engineering Framework).

## How to Use

**Instruction**: Copy the content of `src/dae_minimal_prompt.txt` into any mainstream LLM (GPT-4, Claude 3.5, etc.) to initialize the Elicitation Agent.

## Citation

```bibtex
@article{shao2025dae,
  title={Reducing Alignment Debt in AI Advisory: The Dialogue-as-Elicitation Approach},
  author={Shao, Weishi},
  journal={SSRN},
  year={2025}
}
```

## Contact

1983sirsws@gmail.com
