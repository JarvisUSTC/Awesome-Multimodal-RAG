# 🌟 Awesome Multimodal RAG

A curated list of the latest advancements, papers, tools, and datasets for **Multimodal Retrieval-Augmented Generation (RAG)**. Multimodal RAG integrates information retrieval and generation across multiple data modalities (e.g., text, image, video, audio).

---

## 📚 Contents

- [🌟 Awesome Multimodal RAG](#-awesome-multimodal-rag)
  - [📚 Contents](#-contents)
  - [✨ Introduction](#-introduction)
  - [📝 Papers](#-papers)
    - [📖 Surveys and Tutorials](#-surveys-and-tutorials)
    - [🧠 General Multimodal RAG](#-general-multimodal-rag)
    - [📄 Multimodal Document RAG](#-multimodal-document-rag)
    - [🔍 Domain-Specific Multimodal RAG](#-domain-specific-multimodal-rag)
  - [📊 Datasets](#-datasets)
  - [🔧 Tools and Frameworks](#-tools-and-frameworks)
  - [📈 Benchmarks and Metrics](#-benchmarks-and-metrics)
  - [🚀 Open Challenges](#-open-challenges)
  - [🤝 Contributing](#-contributing)
  - [🙏 Acknowledgments](#-acknowledgments)

---

## ✨ Introduction

**Multimodal RAG** is a cutting-edge approach combining the power of information retrieval and generative models to handle multimodal data. By integrating diverse modalities such as text, images, and audio, Multimodal RAG aims to improve retrieval quality, generate contextually rich outputs, and address complex reasoning tasks. This repository summarizes the latest research, datasets, and tools to foster innovation in this exciting area.

---

## 📝 Papers

### 📖 Surveys and Tutorials
- Comprehensive reviews and overviews of Multimodal RAG.
- **Key Papers:**
  - [📄 Retrieving Multimodal Information for Augmented Generation: A Survey](https://arxiv.org/pdf/2303.10868) - This paper provides a comprehensive overview of the methods and challenges in leveraging multimodal information (e.g., images, audio, video, and structured knowledge) to enhance LLMs. ⏰ *2023-03*

- **Tutorials:**
  - [🛠️ Multimodal RAG for PDFs with Text, Images, and Charts](https://pathway.com/developers/templates/multimodal-rag) ⏰ *2024-06*
  - [🎓 Multimodal Retrieval-Augmented Generation (RAG) with Document Retrieval (ColPali) and Vision Language Models (VLMs)](https://huggingface.co/learn/cookbook/multimodal_rag_using_document_retrieval_and_vlms)
  - [🗂️ A Comprehensive Guide to Building Multimodal RAG Systems](https://www.analyticsvidhya.com/blog/2024/09/guide-to-building-multimodal-rag-systems/) ⏰ *2024-09*

### 🧠 General Multimodal RAG
- **Key Papers:**
  - [🌍 GME: Improving Universal Multimodal Retrieval by Multimodal LLMs](http://arxiv.org/abs/2412.16855) - A robust multimodal embedding model developed by Alibaba, trained on 8 million instances, designed for general multimodal retrieval. It supports single-modal, cross-modal, fused-modal retrieval, and visual documents retrieval. ⏰ *2024-12*
  - [🧩 MegaPairs: Massive Data Synthesis For Universal Multimodal Retrieval](http://arxiv.org/abs/2412.14475) - Introduces a novel data synthesis method to create large-scale synthetic datasets for enhanced multimodal retrieval. ⏰ *2024-12*
  - [🔄 Progressive Multimodal Reasoning via Active Retrieval](http://arxiv.org/abs/2412.14835) - Proposes a progressive reasoning framework leveraging active retrieval for multimodal tasks. ⏰ *2024-12*

### 📄 Multimodal Document RAG
- **Key Papers:**
  - [📚 VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation](http://arxiv.org/abs/2412.10704) ⏰ *2024-12*
  - [🖼️ Unified Multimodal Interleaved Document Representation for Retrieval](http://arxiv.org/abs/2410.02729) ⏰ *2024-12*
  - [🎥 VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents](http://arxiv.org/abs/2410.10594) ⏰ *2024-10*
  - [📘 ColPali: Efficient Document Retrieval with Vision Language Models](http://arxiv.org/abs/2407.01449) ⏰ *2024-07*
  - [🖼️ Unifying Multimodal Retrieval via Document Screenshot Embedding](http://arxiv.org/abs/2406.11251) ⏰ *2024-06*

### 🔍 Domain-Specific Multimodal RAG
- **Key Papers:**
  - [🧬 AlzheimerRAG: Multimodal Retrieval Augmented Generation for PubMed articles](http://arxiv.org/abs/2412.16701) - Focuses on biomedical applications. ⏰ *2024-12*

---

## 📊 Datasets

- **Key Datasets:**
  - [📚 MMDocIR: Benchmarking Multi-Modal Retrieval for Long Documents](https://arxiv.org/abs/2501.08828) - A new benchmark for page-level and layout-level retrieval, aiming to localize relevant pages in long documents and detect specific layouts with finer granularity than whole-page analysis. The data source is primarily derived from existing DocVQA datasets. ⏰ *2024-1*
  - [📚 Document Haystacks: Vision-Language Reasoning Over Piles of  1000+ Documents](http://arxiv.org/abs/2411.16740) - A dataset for mRAG, derived from DocVQA and InfographicVQA, featuring 300 evaluation questions and 3,000 training questions. ⏰ *2024-12*
  - [📚 LongDocURL: a Comprehensive Multimodal Long Document Benchmark Integrating Understanding, Reasoning, and Locating](http://arxiv.org/abs/2412.18424) - A benchmark for Long Document Understanding, Numerical Reasoning, and Cross-Element Locating, comprising 20 sub-tasks and 2,325 QA pairs across 33,000+ document pages. ⏰ *2024-12*
  - [📚 Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent](http://arxiv.org/abs/2411.02937) - A challenging dataset for dynamic RAG tasks. ⏰ *2024-11*
  - [📚 M3DocRAG: Multi-modal Retrieval is What You Need  for Multi-page Multi-document Understanding](http://arxiv.org/abs/2411.04952) - A benchmark for evaluating open-domain DocVQA over 3,000+ PDF documents with 40,000+ pages. ⏰ *2024-11*
  - [📚 M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding And A Retrieval-Aware Tuning Framework](http://arxiv.org/abs/2411.06176) - A benchmark consisting of 851 samples featuring lengthy and diverse multimodal content, including text, figures, and tables, drawn from academic papers, technical manuals, and financial reports. ⏰ *2024-11*
  - [📚 MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations](http://arxiv.org/abs/2407.01523) - A long-context multimodal benchmark of 1,082 expert-annotated questions based on 135 lengthy PDF documents (average 47.5 pages), requiring evidence from diverse sources (text, images, tables, charts) and locations. Notably, 33.7% are cross-page questions, and 20.6% are unanswerable to evaluate hallucination detection. ⏰ *2024-07*
  - [📚 SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers](http://arxiv.org/abs/2407.09413) - A large-scale QA dataset (270k questions, 25k papers) specifically designed to interpret complex figures and tables within the context of scientific research articles across various domains of computer science. ⏰ *2024-07*

---

## 🔧 Tools and Frameworks

- **Notable Projects:**
  - [🔥 Kiln](https://kiln.tech) - Build a RAG in 5 minutes using drag-and-drop. Kiln is a free tool for building production-ready AI systems, supporting RAG pipelines (text, image, audio, video), evaluations, agents, MCP tool-calling, synthetic data generation, and fine-tuning. [GitHub](https://github.com/Kiln-AI/Kiln) ⏰ *2025-11*
  - [🔨 Together Cookbook](https://github.com/togethercomputer/together-cookbook) - It is a collection of code and guides designed to help developers build with open source models using Together AI. ⏰ *2024-12*
  - [📊 Pixeltable](https://github.com/pixeltable/pixeltable) - Declarative multimodal AI data engine supporting document/media chunking, embedding generation, hybrid vector search, and incremental updates for Multimodal RAG. [GitHub](https://github.com/pixeltable/pixeltable) ⏰ *2024-03*

---

## 📈 Benchmarks and Metrics

- **Evaluation Metrics:**
  - **Retrieval Metrics:** Precision@k, Recall@k
  - **Generation Metrics:** BLEU, ROUGE, CIDEr

---

## 🚀 Open Challenges

- **Key Challenges:**
  - Efficient multimodal retrieval at scale
  - Alignment between modalities
  - Handling noisy or incomplete multimodal data
  - Real-time processing for practical applications

---

## 🤝 Contributing

Contributions are welcome! Please submit a pull request or open an issue to add new papers, datasets, tools, or corrections.

---

## 🙏 Acknowledgments

Thanks to the research community for their efforts in advancing Multimodal RAG. If you find this repository useful, please consider starring it!

---
