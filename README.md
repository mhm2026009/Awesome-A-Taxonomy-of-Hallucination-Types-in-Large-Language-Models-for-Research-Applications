# Awesome LLM Hallucinations in Research Applications

A curated collection of research papers, datasets, tools, implementations, and learning resources focused on understanding, classifying, detecting, evaluating, and mitigating hallucinations in Large Language Models (LLMs), with an emphasis on research applications.

## Contents

- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Citation Integrity Audit](#citation-integrity-audit)
- [Survey and Taxonomy Papers](#survey-and-taxonomy-papers)
- [Hallucination Detection](#hallucination-detection)
- [Hallucination Evaluation](#hallucination-evaluation)
- [Hallucination Mitigation](#hallucination-mitigation)
- [Research Applications](#research-applications)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials and Learning Resources](#tutorials-and-learning-resources)
- [References](#references)
- [License](#license)

---

## Overview

Large Language Models have demonstrated impressive capabilities in natural language understanding and generation. However, they can produce information that is factually incorrect, unsupported by evidence, inconsistent with provided context, or internally contradictory. These errors are commonly referred to as hallucinations.

Hallucinations are particularly important in research applications because researchers may use LLMs for literature review, scientific writing, information retrieval, summarization, question answering, and data analysis. Incorrect information or fabricated references can reduce the reliability and reproducibility of research.

This repository provides a structured collection of resources for understanding hallucinations in LLMs. It focuses on different hallucination types, their causes, detection methods, evaluation benchmarks, mitigation techniques, and practical research applications.

The collection emphasizes verification and reproducibility. Research papers and resources are selected based on their relevance and are linked to authoritative sources whenever possible.

---

## AI-Assisted Research Paper

My research paper:

[View AI-Assisted Research Paper](paper/Lab1_MHM2026009_Kushagra_Agrawal_AI_Assisted_Paper.pdf)

**Topic:** A Taxonomy of Hallucination Types in Large Language Models for Research Applications

---

## Citation Integrity Audit

The references and claims used during the research process were checked for authenticity and consistency.

[View Citation Integrity Audit](paper/Lab1_MHM2026009_Kushagra_Agrawal_Audit.pdf)

---

## Survey and Taxonomy Papers

### A Survey on Hallucination in Large Language Models
Lei Huang et al., 2025

A comprehensive survey covering hallucination taxonomy, causes, detection, benchmarks, and mitigation.

[Paper](https://doi.org/10.1145/3703155)

### Large Language Models Hallucination: A Comprehensive Survey
Aisha Alansari and Hamzah Luqman, 2025

Reviews hallucination types, causes, detection approaches, mitigation strategies, and evaluation.

[Paper](https://arxiv.org/abs/2510.06265)

### A Comprehensive Taxonomy of Hallucinations in Large Language Models
Manuel Cossio, 2025

Provides a detailed classification of different hallucination manifestations and their causes.

[Paper](https://arxiv.org/abs/2508.01781)

---

## Hallucination Detection

### SelfCheckGPT
Manakul et al., 2023

A zero-resource approach that detects hallucinations by comparing multiple sampled responses from an LLM.

[Paper](https://aclanthology.org/2023.emnlp-main.557/)

### FACTOOL
Hao et al., 2023

A framework for detecting factual errors in generated content using external tools and evidence.

[Paper](https://arxiv.org/abs/2307.13528)

### Semantic Entropy
Farquhar et al., 2024

Uses semantic uncertainty to identify when model outputs are likely to be incorrect.

[Paper](https://www.nature.com/articles/s41586-024-07421-0)

---

## Hallucination Evaluation

### TruthfulQA

A benchmark designed to test whether language models generate truthful answers instead of reproducing common misconceptions.

[Paper](https://aclanthology.org/2022.acl-long.229/)

### HaluEval

A large-scale benchmark for evaluating hallucination recognition in LLMs.

[Paper](https://aclanthology.org/2023.emnlp-main.397/)

### FActScore

Evaluates factual precision by measuring how many atomic facts in a generation are supported by reliable sources.

[Paper](https://aclanthology.org/2023.emnlp-main.741/)

### RAGTruth

A dataset for evaluating hallucinations in retrieval-augmented generation systems.

[Paper](https://arxiv.org/abs/2401.00396)

---

## Hallucination Mitigation

### Retrieval-Augmented Generation

Uses external knowledge retrieval to provide additional information to the language model.

[Paper](https://arxiv.org/abs/2005.11401)

### Self-RAG

Combines retrieval, generation, and self-reflection to improve response quality.

[Paper](https://arxiv.org/abs/2310.11511)

### Chain-of-Verification

Uses verification questions and independent checking to reduce hallucinated information.

[Paper](https://arxiv.org/abs/2309.11495)

### CRITIC

Explores tool-assisted self-correction of LLM-generated responses.

[Paper](https://arxiv.org/abs/2305.11738)

---

## Research Applications

Hallucination research is especially important in:

- Scientific literature review
- Academic question answering
- Scientific summarization
- Research assistants
- Information retrieval
- Medical research
- Legal research
- Financial research
- Code generation
- Knowledge-intensive question answering

---

## Datasets

| Dataset | Purpose |
|---|---|
| [HaluEval](https://github.com/RUCAIBox/HaluEval) | Hallucination evaluation |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Truthfulness evaluation |
| [RAGTruth](https://arxiv.org/abs/2401.00396) | RAG hallucination detection |

---

## Tools and Libraries

| Tool | Purpose |
|---|---|
| FActScore | Factuality evaluation |
| SelfCheckGPT | Hallucination detection |
| LangChain | LLM application and RAG development |
| LlamaIndex | Data integration for LLM applications |
| Hugging Face Transformers | Transformer and LLM experimentation |

---

## GitHub Implementations

- [HaluEval](https://github.com/RUCAIBox/HaluEval) - Hallucination evaluation benchmark
- [SelfCheckGPT](https://github.com/potsawee/selfcheckgpt) - Black-box hallucination detection
- [FActScore](https://github.com/shmsw25/FActScore) - Factual precision evaluation
- [TruthfulQA](https://github.com/sylinrl/TruthfulQA) - Truthfulness benchmark
- [Self-RAG](https://github.com/AkariAsai/self-rag) - Retrieval and self-reflection

---

## Tutorials and Learning Resources

- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course)
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/)
- [Stanford CS25](https://web.stanford.edu/class/cs25/)
- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/)
- [Papers With Code](https://paperswithcode.com/)

---

## References

A detailed list of verified research papers and resources is available in:

[References](references/references.md)

---

## License

This repository is intended for academic and educational purposes.

The original research papers and resources remain under their respective licenses and copyrights. This repository links to external resources rather than redistributing copyrighted papers.
