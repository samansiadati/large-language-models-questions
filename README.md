# 100 Questions About Large Language Models

## Companion Repository

This repository is a **study companion and practical implementation guide** for the book ***100 Questions About Large Language Models***.

The goal of this project is to provide a **question-driven, practical approach** to understanding large language models (LLMs) by offering:

* Clear, concise explanations of key LLM concepts
* Step-by-step answers with worked examples
* Python implementations and small experiments
* Visualizations to build intuition for model behavior
* Exercises and practice questions for self-study

> 📌 **Important note**: This repository is a **learning aid** and does **not** contain the book itself, nor does it reproduce copyrighted content. All explanations, code, and exercises are original.

---

## 🎯 Who This Repository Is For

This repo is designed for:

* Students learning **LLMs, NLP, or modern AI**
* Practitioners who want to **strengthen their understanding through Q&A**
* Engineers preparing for **interviews on LLMs and transformers**
* Researchers who want a **quick reference and hands-on examples**

If you have ever thought *“I know LLM APIs, but I want to understand the mechanics and theory”*, this repository is for you.

---

## 🧠 Core Topics Covered

The repository follows a question-driven structure covering:

* **Foundations of LLMs** (transformer architecture, attention, positional encoding)
* **Pretraining & Fine-tuning** (transfer learning, domain adaptation)
* **Autoregressive & Encoder-Decoder Models**
* **Model Evaluation** (perplexity, BLEU, ROUGE, accuracy)
* **Practical Applications** (text generation, summarization, QA, chatbots)
* **Deployment & Scaling** (efficient inference, memory optimization)
* **Best Practices** (prompt engineering, safety, ethical considerations)

Each topic is explored through **Q&A**, with explanations, mathematical intuition, and coding examples.

---

## 📂 Repository Structure

```text
large-language-models-questions/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── 01-llm-foundations/
│   ├── README.md
│   ├── transformer_architecture.ipynb
│   ├── attention_mechanisms.ipynb
│   └── positional_encoding.ipynb
│
├── 02-pretraining-fine-tuning/
│   ├── pretraining.ipynb
│   ├── fine_tuning.ipynb
│   └── transfer_learning.ipynb
│
├── 03-autoregressive-encoder-decoder/
│   ├── autoregressive_models.ipynb
│   └── encoder_decoder_models.ipynb
│
├── 04-model-evaluation/
│   ├── perplexity.ipynb
│   ├── bleu_rouge.ipynb
│   └── accuracy_metrics.ipynb
│
├── 05-practical-applications/
│   ├── text_generation.ipynb
│   ├── summarization.ipynb
│   └── question_answering.ipynb
│
├── 06-deployment-scaling/
│   ├── efficient_inference.ipynb
│   ├── memory_optimization.ipynb
│   └── distributed_inference.ipynb
│
├── 07-best-practices/
│   ├── prompt_engineering.ipynb
│   └── ethical_safety_considerations.ipynb
│
└── utils/
    └── plotting.py
