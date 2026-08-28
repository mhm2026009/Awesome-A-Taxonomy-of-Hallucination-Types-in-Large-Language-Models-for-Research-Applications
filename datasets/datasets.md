# Datasets and Benchmarks

This file contains datasets and benchmarks relevant to the detection and
evaluation of hallucinations in Large Language Models.

---

## 1. HaluEval

**Type:** Hallucination evaluation benchmark  
**Authors:** Junyi Li et al.  
**Year:** 2023

**Link:** https://github.com/RUCAIBox/HaluEval

### Description

HaluEval is a large-scale benchmark designed to evaluate hallucination
recognition in Large Language Models. It contains hallucinated and
non-hallucinated responses across multiple tasks.

### Relevance to This Research

HaluEval is directly relevant to the proposed taxonomy because it provides
examples that can be used to study and evaluate different hallucination
behaviours.

### Useful For

- Hallucination detection
- Benchmarking LLMs
- Comparing detection approaches
- Evaluating hallucinated responses

---

## 2. TruthfulQA

**Type:** Truthfulness benchmark  
**Authors:** Stephanie Lin, Jacob Hilton, Owain Evans  
**Year:** 2022

**Link:** https://github.com/sylinrl/TruthfulQA

### Description

TruthfulQA evaluates whether language models produce truthful answers or
repeat common misconceptions.

### Relevance to This Research

It is useful for studying factuality hallucinations, particularly cases where
models produce plausible but incorrect information.

### Useful For

- Factuality evaluation
- Truthfulness testing
- Comparing language models
- Studying factual hallucination

---

## 3. RAGTruth

**Type:** Retrieval-Augmented Generation hallucination corpus

**Link:** https://arxiv.org/abs/2401.00396

### Description

RAGTruth is a corpus designed to study hallucinations in
Retrieval-Augmented Generation systems.

### Relevance to This Research

The research paper identifies RAG as an important task context. RAGTruth is
therefore useful for studying hallucinations that occur even when external
documents are supplied to a model.

### Useful For

- RAG hallucination detection
- Faithfulness evaluation
- Retrieval-grounded generation
- Research on source-grounding errors

---

## Dataset Comparison

| Dataset | Main Focus | Relevance |
|---|---|---|
| HaluEval | General hallucination evaluation | High |
| TruthfulQA | Truthfulness and factuality | High |
| RAGTruth | Hallucinations in RAG | High |

## Limitations

These datasets do not completely cover the proposed research taxonomy.
In particular, dedicated datasets for citation hallucination, methodological
hallucination, source-attribution hallucination, and long multi-step research
workflows remain limited.

Developing research-specific benchmarks covering these categories is an
important future direction.
