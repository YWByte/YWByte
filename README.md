<div align="center">

# Yiwei Zhang

### Software Engineer · Agent Harness & Runtime

I build AI agent systems with a focus on tool orchestration, context engineering, and reliable execution.<br>
My work spans production agent infrastructure, long-context workflows, multi-agent reasoning, and document intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yiwei-zhang-a0a311381/)
[![Email](https://img.shields.io/badge/Email-1F6FEB?style=flat-square&logo=gmail&logoColor=white)](mailto:zyw1137038537@gmail.com)

</div>

---

## `01 / Engineering Focus`

**Agent Harness & Runtime**<br>
On-demand tool discovery, controlled execution, session lifecycle management, and external capability integration.

**Context Engineering**<br>
Retrieval, dynamic context assembly, and factual consistency across long-running workflows.

**Reasoning & Document Intelligence**<br>
Multi-agent reasoning, cross-document evidence discovery, and structured document extraction.

---

## `02 / Selected Engineering Work`

### Tencent Hunyuan · Foundation Model Department

*Algorithm Engineer Intern, Tencent · Oct 2026 — Present*

<br>

### WorkBuddy · Agent Harness & Runtime

*Software Engineer Intern, Tencent · Apr 2026 — Oct 2026*

- Contributed to Tool Search and DeferExecuteTool, replacing full tool-definition injection with on-demand retrieval. Unified argument validation, permission checks, and call routing to reduce context overhead and improve reliability across large tool collections.
- Developed image and video generation tools, along with image-processing and 3D-generation Skills. Integrated remote multimodal services with configuration, temporary credentials, asynchronous task polling, and result delivery.
- Helped design and implement the ACP communication channel between the CLI Server and desktop main process, supporting session creation and recovery, streaming message and tool-state updates, tool approvals, and task cancellation.

> Proprietary production work. Implementation details are intentionally limited.

<br>

### Memoir Generation · Workflow & Context Engineering

*Algorithm Engineer Intern, Tencent · Nov 2025 — Mar 2026*

- Built a staged writing workflow spanning interview segmentation, event extraction, chronological ordering, narrative-arc clustering, chapter planning, writing, and review, turning fragmented interviews into memoirs approaching 100,000 Chinese characters.
- Retrieved relevant events and prior content for each chapter, dynamically assembling interview excerpts, existing chapters, and style instructions. Added fact-checking and revision to reduce factual drift, repetition, and stylistic inconsistency.

<br>

### Bilingual Financial Document QA · RAG & LLM Post-Training

*Project Development Intern, Shenzhen Sunline Tech · Apr 2024 — Oct 2024*

- Built a Chinese–English financial document QA system combining retrieval augmentation and model fine-tuning, improving accuracy by approximately 20% over the baseline model and a naive RAG baseline.
- Created bilingual instruction data and model-generated preference pairs for SFT and DPO, improving citation correctness, cross-language answer consistency, and abstention when evidence was insufficient.

<br>

### JSONPlacement · Reliable Structured Generation

*First Author · arXiv preprint · Submitted to NAACL 2027*

- Studied placement failures in LLM-generated JSON, where correct values can be assigned to the wrong records or nesting levels. Introduced JSONPlacement to isolate placement from value extraction across six open-weight models.
- Distinguished record-assignment failures from hierarchy-construction failures, then tested traversal-aligned inputs and per-record path outputs as separate and combined interventions.
- The combined approach produced exact outputs for three 8–12B models on every newly generated synthetic instance and a real-data validation set.

[arXiv](https://arxiv.org/abs/2608.25358)

<br>

### AuditAgent · Multi-Agent Financial Evidence Discovery

*Core Developer · Feb 2025 — Sep 2025 · ICAIF 2025*

- Turned expert financial-review practices into a staged workflow for risk screening, report verification, and cross-period comparison. Combined risk priors with sparse and dense retrieval to assemble relevant report passages and historical evidence into traceable problem–report–evidence chains.
- Constructed FinFraud-Real from 1,570 regulatory fraud cases and associated financial reports for cross-document evidence discovery and evaluation.

[Paper](https://dl.acm.org/doi/10.1145/3768292.3770383) · [arXiv](https://arxiv.org/abs/2510.00156)

<br>

### HybriDoc · End-to-End Document Structure Extraction

*Technical Lead, two-person team · May 2025 — Sep 2025 · CCKS 2025 — 1st Place*

- Solely designed and implemented an adaptive PDF-to-Markdown pipeline integrating multiple OCR modules with LLM- and tree-based structure correction.
- Handled complex layouts, cross-page tables, and formulas, achieving first place in the CCKS 2025 End-to-End Document Structure Extraction Evaluation, with results published at CCKS 2025.

---

## `03 / Technical Foundation`

**Languages** — Python · TypeScript · C++<br>
**LLMs & Agents** — Tool calling & orchestration · MCP · RAG · Multi-agent reasoning · Context management · Long-text & multimodal workflows<br>
**Engineering** — API & model-service integration · Authentication · Service routing · Request tracing · Asynchronous execution · Structured logging · Regression testing<br>
**Document Intelligence** — OCR integration · Structured document extraction · Tables & formulas · HTML / LaTeX / Markdown conversion

---

## `04 / Education`

**Shenzhen University** · Master's in Computer Science and Technology<br>
Sep 2024 — Expected Jun 2027<br>
Research: LLM agents, RAG, multi-agent systems, long-context workflows, and document intelligence.

---

## `05 / Publications & Research`

- **ICAIF 2025 · Published** — AuditAgent: Expert-Guided Multi-Agent Reasoning for Cross-Document Fraudulent Evidence Discovery. [Paper](https://dl.acm.org/doi/10.1145/3768292.3770383) · [arXiv](https://arxiv.org/abs/2510.00156)
- **CCKS 2025 · Published** — HybriDoc: An Adaptive Multi-Path Framework for End-to-End Document Structure Extraction.
- **arXiv preprint** — Context Prologue: Recoverable Context Compilation for Tool-Using Agents.
- **Submitted to NAACL 2027 · First Author · arXiv preprint** — Right Values, Wrong Places: Diagnosing and Fixing Record Misplacement in LLM-Generated JSON. [arXiv](https://arxiv.org/abs/2608.25358)

---

<div align="center">

**Open to software engineering and AI agent opportunities in London.**

[LinkedIn](https://www.linkedin.com/in/yiwei-zhang-a0a311381/) · [Email](mailto:zyw1137038537@gmail.com)

</div>
