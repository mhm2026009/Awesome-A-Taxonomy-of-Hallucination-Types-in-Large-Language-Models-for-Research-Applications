# Tools and Libraries

This collection contains tools and libraries useful for detecting,
evaluating, mitigating, or experimenting with hallucinations in Large
Language Models.

---

## 1. FActScore

**Purpose:** Factuality evaluation

**Repository:** https://github.com/shmsw25/FActScore

### Description

FActScore evaluates the factual precision of long-form generated text by
breaking the output into atomic facts and checking whether those facts are
supported by a knowledge source.

### Relevance

This is highly relevant to research applications because literature reviews
and research summaries often contain many individual factual claims.

---

## 2. SelfCheckGPT

**Purpose:** Black-box hallucination detection

**Repository:** https://github.com/potsawee/selfcheckgpt

### Description

SelfCheckGPT uses multiple sampled responses from an LLM and measures their
consistency to identify potentially hallucinated content.

### Relevance

It represents the sampling-based detection approach discussed in the
research paper.

---

## 3. LangChain

**Purpose:** LLM application development

**Website:** https://www.langchain.com/

### Description

LangChain provides components for building LLM applications, including
retrieval-augmented generation, tool use, and document-based workflows.

### Relevance

It can be used to build research assistants that retrieve external sources
before generating answers.

---

## 4. LlamaIndex

**Purpose:** Connecting LLMs with external data

**Website:** https://www.llamaindex.ai/

### Description

LlamaIndex provides tools for connecting language models to external
documents and data sources.

### Relevance

External grounding is important for reducing factuality and faithfulness
problems in research-oriented LLM applications.

---

## 5. Hugging Face Transformers

**Purpose:** LLM experimentation and model development

**Website:** https://huggingface.co/docs/transformers/

### Description

Transformers provides access to a large ecosystem of pretrained language
models and tools for experimentation.

### Relevance

Researchers can use it to evaluate different models and investigate
hallucination behaviour under different prompts, models, and datasets.

---

## Tool Categories

| Tool | Main Function | Hallucination Relevance |
|---|---|---|
| FActScore | Factuality evaluation | Direct |
| SelfCheckGPT | Hallucination detection | Direct |
| LangChain | RAG and LLM applications | Mitigation / Research |
| LlamaIndex | Data grounding | Mitigation / Research |
| Transformers | Model experimentation | Evaluation / Research |

## Research Use

These tools can support the development of hallucination-aware research
systems, particularly systems that combine retrieval, factuality checking,
source attribution, and uncertainty estimation.
