# GitHub Implementations

This file contains open-source implementations relevant to hallucination
detection, evaluation, benchmarking, and mitigation in Large Language Models.

---

## 1. HaluEval

**Repository:** https://github.com/RUCAIBox/HaluEval

### What It Provides

The HaluEval repository provides the benchmark data and resources for
evaluating hallucination recognition in Large Language Models.

### Relevance

It directly supports experimentation with hallucination detection and
evaluation.

---

## 2. SelfCheckGPT

**Repository:** https://github.com/potsawee/selfcheckgpt

### What It Provides

An implementation of the SelfCheckGPT approach for black-box hallucination
detection.

### Relevance

Useful for studying sampling-based consistency as a hallucination signal.

---

## 3. FActScore

**Repository:** https://github.com/shmsw25/FActScore

### What It Provides

An implementation for evaluating factual precision in long-form generated
text.

### Relevance

Especially relevant to research writing, where long-form outputs can contain
many individual factual claims.

---

## 4. TruthfulQA

**Repository:** https://github.com/sylinrl/TruthfulQA

### What It Provides

Dataset and evaluation resources for testing model truthfulness.

### Relevance

Useful for evaluating factuality-related hallucinations and comparing
different language models.

---

## 5. Self-RAG

**Repository:** https://github.com/AkariAsai/self-rag

### What It Provides

An implementation of Self-RAG, which combines retrieval, generation, and
self-reflection.

### Relevance

Self-RAG is relevant to hallucination mitigation because it attempts to
ground generation in retrieved information while allowing the model to
reflect on its output.

---

## Comparison

| Repository | Main Focus | Role |
|---|---|---|
| HaluEval | Hallucination benchmark | Evaluation |
| SelfCheckGPT | Hallucination detection | Detection |
| FActScore | Factual precision | Evaluation |
| TruthfulQA | Truthfulness | Evaluation |
| Self-RAG | Retrieval + self-reflection | Mitigation |

## Research Relevance

Together, these implementations cover several important stages of a
hallucination-aware research workflow:

**Retrieve → Generate → Evaluate → Detect → Reflect/Mitigate**

They can therefore serve as starting points for future research into
hallucination-aware academic and scholarly LLM systems.
