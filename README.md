# Awesome Arabic AI 🌐🤖

> A curated, bilingual (العربية / English) list of resources for building Arabic-first AI, LLMs, and NLP systems.
> Maintained by [@faresrafat3](https://github.com/faresrafat3) · 💼 [Hire me on Mostaql](https://mostaql.com/u/faresrafat3)

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e882/ad/awesome.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A living, community-driven index of the best open models, datasets, benchmarks, tools, and papers for **Arabic language AI**. If you build chatbots, RAG systems, or agents that need to understand and speak Arabic correctly — start here.

---

## 📑 Table of Contents
- [🤖 Models](#-models)
- [📚 Datasets](#-datasets)
- [🛠️ Tools & Libraries](#️-tools--libraries)
- [📊 Benchmarks & Eval](#-benchmarks--eval)
- [📄 Papers](#-papers)
- [🎓 Courses & Communities](#-courses--communities)
- [💡 Project Ideas](#-project-ideas)

---

## 🤖 Models
- **[AraBERT](https://huggingface.co/aubmindlab/bert-base-arabert)** — SOTA Arabic BERT for classification & NER.
- **[Jais](https://huggingface.co/inceptionai/jais-13b)** — Open bilingual (Arabic/English) LLM by Inception.
- **[AceGPT](https://huggingface.co/FreedomIntelligence/AceGPT-7B)** — Arabic-centric instruction-tuned LLM.
- **[ALLaM](https://huggingface.co/humain-ai/ALLaM-7B-Instruct-preview)** — Saudi-developed Arabic LLM family. (Original `allam-ai` org URL 404s; model now lives under `humain-ai`.)
- **[QariB](https://huggingface.co/ahmedabdelali/bert-base-qarib)** — Lightweight Arabic reasoning model. (Original `QARI-AI/QariB-1B` URL 404s; closest active QariB model on HF is `ahmedabdelali/bert-base-qarib`.)
- **[Arabic wav2vec2 XLSR-53](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-arabic)** — Most-downloaded Arabic speech recognition model on HF (~2.5M downloads as of 2026-09-04). Fine-tuned from Facebook AI's XLSR-53 on Arabic Common Voice.
- **[Arabic SBERT](https://huggingface.co/akhooli/Arabic-SBERT-100K)** — Sentence-level Arabic embeddings for semantic similarity, clustering, and retrieval. (AR)

## 📚 Datasets
- **[Arabic MTEB](https://huggingface.co/datasets?other=mteb)** — Benchmark suite for Arabic embeddings. (Original `Intron-lab/ArabicMTEB` URL 404s; the MTEB org now hosts Arabic tasks under the [mteb](https://huggingface.co/mteb) namespace.)
- **[CAMeL Lab Arabic NER](https://camel-lab.com)** — Annotated NER corpora (ANERcorp, ANERcorp-Camel, etc.) from NYU Abu Dhabi. (AR)
- **[Arabic Speech Corpus](https://arabicspeech.com)** — Phonetically annotated Quranic/Modern Standard Arabic.
- **[SemEval Arabic Sentiment](https://alt.qcri.org/semeval2017/task4/)** — Sentiment analysis datasets.

## 🛠️ Tools & Libraries
- **[CamelTools](https://github.com/CAMeL-Lab/camel_tools)** — Morphology, disambiguation, NER, sentiment for Arabic.
- **[pyarabic](https://github.com/linuxscout/pyarabic)** — Arabic text processing utilities.
- **[Farasa](https://github.com/MagedSaeed/farasapy)** — Fast Arabic segmentation & stemming. (Original `qcri/farasa` URL 404s; the active Python wrapper is `MagedSaeed/farasapy`.)
- **[Tashaphyne](https://github.com/linuxscout/tashaphyne)** — Light stemmer for Arabic.
- **[ARLLM (my related work)](https://github.com/faresrafat3/semitic-router)** — Hybrid neural/symbolic routing for Semitic morphology.

## 📊 Benchmarks & Eval
- **[ArabicMMLU](https://huggingface.co/datasets?other=OpenLLM-Arabic)** — Multitask Arabic understanding eval. (Original `OpenLLM-Arabic/OpenLLM-Arabic-Eval` URL 404s; OpenLLM-Arabic still publishes under the [OpenLLM-Arabic](https://huggingface.co/OpenLLM-Arabic) org.)
- **[ORCA: A Challenging Benchmark for Arabic Language Understanding](https://arxiv.org/abs/2212.10758)** (Elmadany et al., 2023) — Cross-task Arabic understanding benchmark with model performance leaderboard. (AR)
- **[CAMEL-Bench: A Comprehensive Arabic LMM Benchmark](https://arxiv.org/abs/2410.18976)** (Ghosh et al., 2024) — Multimodal benchmark for Arabic large multimodal models. (AR/EN)
- **[ARB: A Comprehensive Arabic Multimodal Reasoning Benchmark](https://arxiv.org/abs/2505.17021)** (Khalid et al., 2025) — Multimodal reasoning across images, charts, and documents in Arabic. (AR/EN)
- **[Arabic LLM Leaderboard](https://huggingface.co/spaces?other=arabic-llm)** — Community leaderboard. (Original `imomayiz/arabic-llm-leaderboard` Space 404s; current Arabic LLM leaderboards on HF are searchable under the [arabic-llm tag](https://huggingface.co/spaces?other=arabic-llm).)

## 📄 Papers
- **[AraBERT: Transformer-based Model for Arabic Language Understanding](https://arxiv.org/abs/2003.00104)** (Antoun et al., 2020) — Original Arabic BERT; the canonical baseline for classification & NER. (AR/EN)
- **[AraT5: Text-to-Text Transformers for Arabic Language Generation](https://arxiv.org/abs/2109.12068)** (Nagoudi et al., 2022) — Arabic T5 family for generation, summarization, and seq2seq. (AR/EN)
- **[Jais and Jais-chat: Arabic-Centric Foundation and Instruction-Tuned Open Generative LLMs](https://arxiv.org/abs/2308.16149)** (Sengupta et al., 2023) — 13B/30B/70B Arabic-centric decoder LLM with bilingual instruction tuning. (AR/EN)
- **[AceGPT: Localizing Large Language Models in Arabic](https://arxiv.org/abs/2309.12053)** (Huang et al., 2024) — Arabic-LLaMA fine-tune with cultural alignment. (AR/EN)
- **[ALLaM: Large Language Models for Arabic and English](https://arxiv.org/abs/2407.15390)** (Bari et al., 2024) — Saudi-developed Arabic/English LLM with explicit ArabicNLP evaluation. (AR/EN)
- **[Fanar: An Arabic-Centric Multimodal Generative AI Platform](https://arxiv.org/abs/2501.13944)** (Team Fanar, 2025) — Arabic-centric multimodal platform (text + image + speech). (AR/EN)
- **[CAMEL-Bench: A Comprehensive Arabic LMM Benchmark](https://arxiv.org/abs/2410.18976)** (Ghosh et al., 2024) — Comprehensive multimodal benchmark for Arabic LMMs. (AR/EN)
- **[Cognitive Economy in LLM Routing](https://github.com/faresrafat3/ai-cost-library)** — Bilingual evidence-based library on cost-vs-quality tradeoffs across Arabic LLM tiers. (AR/EN)

## 🎓 Courses & Communities
- **[Arabic NLP Reading Group](https://twitter.com/ArabicNLP)** — ACL Arabic NLP SIG.
- **[CAMeL Lab](https://camel-lab.com)** — Research group at NYU Abu Dhabi (Arabic morphology, NER, dialect ID).
- **[Hugging Face Arabic community](https://huggingface.co/models?other=arabic)** — Models & discussions. (Original `huggingface.co/arabic` URL 404s; the active Arabic-tagged resources are at [models?other=arabic](https://huggingface.co/models?other=arabic).)
- **[r/LanguageTechnology](https://reddit.com/r/LanguageTechnology)** — Broad NLP, Arabic threads common.

## 💡 Project Ideas
1. Build a RAG chatbot over an Arabic PDF library (try my [RAG SaaS Starter](https://github.com/faresrafat3/rag-saas-starter)).
2. Fine-tune a small model for Egyptian/Dialect classification.
3. Add Arabic RTL support + streaming to any open LLM UI.
4. Benchmark cost vs. quality across Jais / AceGPT / ALLaM for your use case.
5. **Replicate [AraBERT's NER pipeline](https://arxiv.org/abs/2003.00104) on a dialectal corpus** (Egyptian/Gulf/Levantine) and report the F1 drop vs. MSA — dialectal Arabic is the most underserved slice of the stack.

---

## 🤝 Contributing
Found a great Arabic AI resource? PRs are welcome! Read [CONTRIBUTING.md](CONTRIBUTING.md).
Please keep entries bilingual-labeled (AR/EN) and citation-backed.

## 📜 License
Content under [MIT](LICENSE) — link back to this list when reusing.
