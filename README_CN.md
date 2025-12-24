# 降低人工智能顾问中的对齐债务：对话即挖掘 (DaE) 框架

![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## 摘要 (Abstract)

在新兴的人工智能顾问服务市场中，用户与 AI 代理之间存在着根本性的“委托-代理问题”。用户受困于“粘性信息”，使得通过临时的提示词工程来传递隐性的偏好变得昂贵且低效。这种摩擦导致了“对齐债务”。我们提出了“对话即挖掘”(Dialogue-as-Elicitation, DaE) 机制，将对齐过程从“事后修正”转变为“事前挖掘”。DaE 采用双代理架构来构建“个人战略资产”——一种结构化的、可复用的用户属性账本。

## 仓库内容 (Repository Contents)

*   `src/dae_minimal_prompt.txt`: 用于挖掘代理和应用代理的操作性最小提示词。
*   `papers/`:
    *   `dae_ssrn.pdf`: **SSRN 版本** (侧重：管理学、对齐债务与经济机制)。
    *   `dae_arxiv_draft.pdf`: **ArXiv 草稿** (侧重：技术实现与工程框架)。

## 使用说明 (How to Use)

**操作指南**：将 `src/dae_minimal_prompt.txt` 的内容复制到任何主流大语言模型（GPT-4, Claude 3.5, DeepSeek 等）中，以初始化挖掘代理。

## 引用 (Citation)

```bibtex
@article{shao2025dae,
  title={Reducing Alignment Debt in AI Advisory: The Dialogue-as-Elicitation Approach},
  author={Shao, Weishi},
  journal={SSRN},
  year={2025}
}
```

## 联系方式 (Contact)

1983sirsws@gmail.com
