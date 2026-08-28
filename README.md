# Awesome LLM Hallucinations in Research Applications

A curated collection of research papers, datasets, tools, GitHub
implementations, and learning resources related to hallucinations in
Large Language Models (LLMs), with a focus on research and scholarly
applications.

---

## 📌 Overview

Large Language Models have become increasingly useful for research tasks
such as literature review, scientific writing, summarization, question
answering, information retrieval, citation generation, and research
assistance.

However, LLMs can generate information that is incorrect, unsupported by
evidence, inconsistent with the provided context, or completely fabricated.
These errors are commonly referred to as **hallucinations**.

This repository accompanies the research paper:

> **A Taxonomy of Hallucination Types in Large Language Models for Research
> Applications**

The repository organizes research resources related to the classification,
detection, evaluation, and mitigation of hallucinations in LLMs.

---

# 📄 Research Paper

## A Taxonomy of Hallucination Types in Large Language Models for Research Applications

The main research paper for this project proposes a multi-axis taxonomy for
classifying hallucinations in research-oriented LLM applications.

The taxonomy considers:

- Origin
- Evaluative target
- Content type
- Task context

### Research Paper

[View Research Paper](paper/AI_Assisted_Research_Paper.pdf)

---

# 🔍 Citation Integrity Audit

An AI-assisted citation integrity audit was conducted as part of the
research process.

The audit focused on checking whether selected references were genuine and
whether their bibliographic information matched the corresponding research
claims.

The verification included:

- Authenticity of the source
- Title
- Authors
- Publication year
- Venue
- DOI or URL
- Consistency with the research claims

### Citation Audit

[View Citation Integrity Audit](citation-audit/Citation_Integrity_Audit.pdf)

---

# 🧠 Proposed Hallucination Taxonomy

The research paper proposes a **multi-axis taxonomy** for understanding
hallucinations in research applications of Large Language Models.

The taxonomy considers four complementary dimensions.

---

## 1. Origin

### Intrinsic Hallucination

Information conflicts with the provided source, document, or context.

### Extrinsic Hallucination

Information cannot be supported by the provided source or context.

---

## 2. Evaluative Target

### Factuality Hallucination

The generated information is factually incorrect or unsupported by reliable
evidence.

### Faithfulness Hallucination

The generated output does not faithfully represent the provided source,
context, or retrieved evidence.

---

## 3. Content Type

The research identifies several content-specific hallucination categories:

- **Entity and Attribute Hallucination**
- **Citation and Reference Hallucination**
- **Numerical and Statistical Hallucination**
- **Methodological and Procedural Hallucination**
- **Logical and Reasoning Hallucination**
- **Source-Attribution Hallucination**

These categories are particularly relevant to academic and research
workflows.

---

## 4. Task Context

Hallucinations are also considered according to the task in which they occur:

- **Closed-Book Generation**
- **Retrieval-Augmented Generation (RAG)**
- **Long-Form and Multi-Step Synthesis**

A single hallucinated response may belong to multiple categories across
different axes.

---

# 📚 Research Papers

This repository contains **20 research papers** related to hallucination
taxonomy, factuality, faithfulness, detection, evaluation, citation errors,
retrieval-augmented generation, and hallucination mitigation.

---

## Survey and Taxonomy

### 1. A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions

**Year:** 2025

A comprehensive survey covering hallucination taxonomy, causes, detection,
benchmarks, and mitigation.

[Paper](https://doi.org/10.1145/3703155)

---

### 2. Survey of Hallucination in Natural Language Generation

**Year:** 2023

Reviews hallucinations in natural language generation and discusses
factuality and faithfulness.

[Paper](https://doi.org/10.1145/3571730)

---

### 3. A Survey of Hallucination in Large Foundation Models

**Year:** 2023

Reviews hallucination phenomena in large foundation models and discusses
different classification approaches.

[Paper](https://arxiv.org/abs/2309.05922)

---

### 4. Cognitive Mirage: A Review of Hallucinations in Large Language Models

**Year:** 2023

Examines hallucinations and their relationship with reasoning and
multi-step generation.

[Paper](https://arxiv.org/abs/2309.06794)

---

### 5. Siren's Song in the AI Ocean: A Survey on Hallucination in Large Language Models

**Year:** 2023

Surveys different hallucination mechanisms and their relationship with
model inputs, context, and factual knowledge.

[Paper](https://arxiv.org/abs/2309.01219)

---

## Factuality and Faithfulness

### 6. On Faithfulness and Factuality in Abstractive Summarization

**Year:** 2020

Introduces influential distinctions between different forms of hallucination
in abstractive summarization.

[Paper](https://aclanthology.org/2020.acl-main.173/)

---

### 7. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks

**Year:** 2020

Introduces Retrieval-Augmented Generation, combining language generation
with external knowledge retrieval.

[Paper](https://arxiv.org/abs/2005.11401)

---

### 8. Fabrication and Errors in the Bibliographic Citations Generated by ChatGPT

**Year:** 2023

Examines fabricated and incorrect bibliographic citations generated by
ChatGPT.

[Paper](https://doi.org/10.1038/s41598-023-41032-5)

---

### 9. Large Legal Fictions: Profiling Legal Hallucinations in Large Language Models

**Year:** 2024

Studies hallucinations involving fabricated or incorrect legal information.

[Paper](https://doi.org/10.1093/jla/laae003)

---

## Hallucination Detection and Evaluation

### 10. TruthfulQA: Measuring How Models Mimic Human Falsehoods

**Year:** 2022

A benchmark designed to evaluate whether language models produce truthful
answers rather than reproducing common misconceptions.

[Paper](https://aclanthology.org/2022.acl-long.229/)

---

### 11. HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models

**Year:** 2023

A large-scale benchmark for evaluating hallucination recognition in LLMs.

[Paper](https://aclanthology.org/2023.emnlp-main.397/)

---

### 12. FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation

**Year:** 2023

Evaluates factual precision by decomposing generated text into atomic
factual claims.

[Paper](https://aclanthology.org/2023.emnlp-main.741/)

---

### 13. SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models

**Year:** 2023

Uses consistency across multiple sampled responses to identify potential
hallucinations.

[Paper](https://aclanthology.org/2023.emnlp-main.557/)

---

### 14. Detecting Hallucinations in Large Language Models Using Semantic Entropy

**Year:** 2024

Uses semantic uncertainty to identify outputs that are likely to contain
hallucinations.

[Paper](https://doi.org/10.1038/s41586-024-07421-0)

---

### 15. A Comprehensive Survey of Hallucination Mitigation Techniques in Large Language Models

**Year:** 2024

Reviews prompting, retrieval, fine-tuning, self-refinement, and other
approaches for reducing hallucinations.

[Paper](https://arxiv.org/abs/2401.01313)

---

### 16. Why Language Models Hallucinate

**Year:** 2025

Provides a theoretical perspective on why hallucinations occur and discusses
the role of training and evaluation incentives.

[Paper](https://arxiv.org/abs/2509.04664)

---

## Additional Factuality and Research-Application Papers

### 17. FELM: Benchmarking Factuality Evaluation of Large Language Models

**Year:** 2023

Introduces a benchmark for evaluating factuality across diverse domains,
including world knowledge, science and technology, writing, reasoning, and
mathematics.

[Paper](https://arxiv.org/abs/2310.00741)

---

### 18. FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios

**Year:** 2023

Presents a framework for detecting factual errors across multiple tasks and
domains, including scientific literature review, mathematical reasoning,
code generation, and knowledge-based question answering.

[Paper](https://arxiv.org/abs/2307.13528)

---

### 19. RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models

**Year:** 2024

Introduces a corpus for studying hallucinations in Retrieval-Augmented
Generation systems.

[Paper](https://aclanthology.org/2024.acl-long.585/)

---

### 20. Long-form factuality in large language models

**Year:** 2024

Introduces LongFact and SAFE for evaluating factuality in long-form answers.
The work decomposes responses into individual facts and checks their support
using search-based evidence.

[Paper](https://arxiv.org/abs/2403.18802)

[Official Code](https://github.com/google-deepmind/long-form-factuality)

---

## Detailed References

The complete collection of papers, descriptions, and their relevance to the
research taxonomy is available here:

👉 [View All Research References](references/references.md)

---

# 📊 Datasets and Benchmarks

Datasets and benchmarks are essential for evaluating hallucination detection
methods and comparing the reliability of different LLMs.

---

## 1. HaluEval

**Purpose:** Hallucination evaluation

HaluEval is a large-scale benchmark containing hallucinated and
non-hallucinated responses for evaluating hallucination recognition.

[GitHub Repository](https://github.com/RUCAIBox/HaluEval)

---

## 2. TruthfulQA

**Purpose:** Truthfulness and factuality evaluation

TruthfulQA evaluates whether language models generate truthful answers
instead of reproducing common misconceptions.

[GitHub Repository](https://github.com/sylinrl/TruthfulQA)

---

## 3. RAGTruth

**Purpose:** RAG hallucination detection

RAGTruth is designed to study hallucinations in Retrieval-Augmented
Generation systems.

[Paper](https://aclanthology.org/2024.acl-long.585/)

---

## Dataset Relevance

These datasets cover important parts of the proposed taxonomy:

| Dataset | Main Focus | Related Taxonomy |
|---|---|---|
| HaluEval | Hallucination recognition | Detection |
| TruthfulQA | Truthfulness | Factuality |
| RAGTruth | RAG hallucination | Faithfulness / Task Context |

However, research-specific datasets for categories such as citation,
methodological, source-attribution, and long-form research hallucinations
remain limited.

👉 [View Dataset Details](datasets/datasets.md)

---

# 🛠️ Tools and Libraries

The following tools can support experimentation with LLM hallucinations.

| Tool | Main Purpose |
|---|---|
| FActScore | Factuality evaluation |
| SelfCheckGPT | Hallucination detection |
| LangChain | LLM applications and RAG |
| LlamaIndex | Connecting LLMs with external data |
| Hugging Face Transformers | LLM experimentation |

---

## FActScore

Measures factual precision in long-form generated text.

[GitHub](https://github.com/shmsw25/FActScore)

---

## SelfCheckGPT

Provides methods for black-box hallucination detection using consistency
between sampled responses.

[GitHub](https://github.com/potsawee/selfcheckgpt)

---

## LangChain

Provides components for building LLM applications, including retrieval,
tool use, and RAG pipelines.

[Website](https://www.langchain.com/)

---

## LlamaIndex

Provides tools for connecting LLMs with external documents and data.

[Website](https://www.llamaindex.ai/)

---

## Hugging Face Transformers

Provides pretrained Transformer models and tools for experimentation with
modern NLP and LLM systems.

[Documentation](https://huggingface.co/docs/transformers/)

---

👉 [View Detailed Tools List](tools/tools.md)

---

# 💻 GitHub Implementations

Open-source implementations make it possible to reproduce and experiment
with hallucination detection, evaluation, and mitigation approaches.

---

## 1. HaluEval

Hallucination evaluation benchmark and supporting resources.

[GitHub Repository](https://github.com/RUCAIBox/HaluEval)

---

## 2. SelfCheckGPT

Implementation of a black-box hallucination detection approach based on
consistency between sampled responses.

[GitHub Repository](https://github.com/potsawee/selfcheckgpt)

---

## 3. FActScore

Implementation for evaluating factual precision in long-form generated text.

[GitHub Repository](https://github.com/shmsw25/FActScore)

---

## 4. TruthfulQA

Dataset and evaluation resources for testing model truthfulness.

[GitHub Repository](https://github.com/sylinrl/TruthfulQA)

---

## 5. Self-RAG

Implementation of Retrieval-Augmented Generation with self-reflection.

[GitHub Repository](https://github.com/AkariAsai/self-rag)

---

## 6. Long-form Factuality

Official implementation of LongFact and SAFE for evaluating long-form
factuality.

[GitHub Repository](https://github.com/google-deepmind/long-form-factuality)

---

👉 [View Detailed GitHub Implementations](implementations/github-repositories.md)

---

# 🎓 Tutorials and Learning Resources

The following resources provide background knowledge useful for understanding
LLMs, NLP, Transformers, retrieval, and research-oriented AI systems.

---

## 1. Hugging Face NLP Course

A practical introduction to Natural Language Processing and Transformer-based
models.

[Course](https://huggingface.co/learn/nlp-course)

---

## 2. Stanford CS224N

A university-level course covering Natural Language Processing and modern
language models.

[Course Website](https://web.stanford.edu/class/cs224n/)

---

## 3. Stanford CS25: Transformers United

Lectures and talks covering Transformers and modern LLM research.

[Course Website](https://web.stanford.edu/class/cs25/)

---

## 4. Hugging Face Transformers Documentation

Documentation for using and experimenting with Transformer models.

[Documentation](https://huggingface.co/docs/transformers/)

---

## 5. Papers With Code

A platform for discovering research papers, datasets, benchmarks, and
implementations.

[Website](https://paperswithcode.com/)

---

# 🔬 Research Applications

Hallucination is especially important when LLMs are used for:

- Academic literature reviews
- Scientific writing
- Research summarization
- Research question answering
- Information retrieval
- Citation generation
- Scientific knowledge synthesis
- Research assistants
- Long-form research generation
- Methodology and procedural recommendations

Incorrect or fabricated information in these applications can affect the
accuracy, reliability, and reproducibility of research.

---

# ⚠️ Key Research Challenges

Several challenges remain in hallucination research:

### 1. Lack of a Universal Taxonomy

Different studies use different terminology and classification schemes.

### 2. Difficulty in Detection

Hallucinated information can be fluent, plausible, and difficult to
distinguish from correct information.

### 3. Limited Research-Specific Benchmarks

Many existing benchmarks focus on general factuality rather than realistic
research workflows.

### 4. Citation Hallucination

LLMs may generate fabricated or incorrect references, DOIs, authors, or
publication details.

### 5. Source Attribution

A model may provide a source that does not actually support the generated
claim.

### 6. Long-Form Generation

Long research answers contain many individual factual claims, making
verification increasingly difficult.

### 7. Retrieval-Augmented Generation

Retrieval can improve grounding but does not completely eliminate
hallucinations.

---

# 🚀 Future Research Directions

Potential directions for future research include:

- Developing standardized hallucination taxonomies
- Creating research-specific hallucination benchmarks
- Improving citation verification
- Developing better source-attribution methods
- Combining retrieval with hallucination detection
- Improving uncertainty estimation
- Developing systems that can abstain when evidence is insufficient
- Evaluating hallucinations across different research domains
- Developing better evaluation methods for long-form research generation
- Creating datasets specifically focused on research hallucinations

---

# 📁 Repository Structure

```text
awesome-llm-hallucinations/
│
├── README.md
│
├── paper/
│   └── AI_Assisted_Research_Paper.pdf
│
├── citation-audit/
│   └── Citation_Integrity_Audit.pdf
│
├── references/
│   └── references.md
│
├── datasets/
│   └── datasets.md
│
├── tools/
│   └── tools.md
│
├── implementations/
│   └── github-repositories.md
│
└── LICENSE
