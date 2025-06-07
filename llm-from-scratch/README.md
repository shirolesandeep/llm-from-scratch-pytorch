# 🧠 LLM From Scratch – My Learning Journey

Welcome! This repository documents my journey of **building a Large Language Model (LLM) from scratch**, inspired by research papers, open-source work, and hands-on coding practice.

This is a **personal learning log**, structured day-by-day, where I implement LLM components step-by-step — from tokenization to training and fine-tuning.

---

## 🔁 Why This Project?

- To deeply understand the internals of LLMs (beyond using pre-built libraries).
- To implement foundational concepts like tokenization, embeddings, attention, transformers, and RLHF.
- To learn by building — from a minimal tokenizer to training GPT-2-style models.

---

## 🗓️ Learning Flow

| Day | Topics | Notebooks/Files |
|-----|--------|------------------|
| Day 1 | Basics of LLMs, RNN, LSTM, Paper Reading | `day1_fundamentals/notes.md` |
| Day 2 | Tokenization, BPE | `Tokenizer.ipynb`, `Bytepairencoding.ipynb` |
| Day 3 | Embeddings, Input-Target Data | `TargetPair.ipynb`, `TokenEmbedding.ipynb`, `PositionalTokenEmbedding.ipynb` |
| Day 4 | Attention Theory | `day4_attention_theory/notes.md` |
| Day 5 | Attention Implementation | `SimplifiedAttention.ipynb`, `SelfAttention.ipynb`, `CasualAttention.ipynb` |
| Day 6 | Multi-Head Attention | `Multihead.ipynb` |
| Day 7 | GPT-2 Core Modules | `LayerNorm.ipynb`, `Gelu.ipynb`, `ShortCutconnection.ipynb` |
| Day 8 | Transformer Block, Loss, Training | `Transformer.ipynb`, `GPT2.ipynb`, `Loss.ipynb` |
| Day 9 | Evaluation & Sampling | `GPT2_entirePretraining.ipynb`, `TOP-Ksampling.ipynb` |
| Day 10 | Weight Handling | `Save_Load_weights.ipynb`, `774M_weights.ipynb` |
| Day 11 | Classification Fine-Tuning | `SpamClassificationFinetuned.ipynb` |
| Day 12 | Instruction Fine-Tuning | `InstructionFinetuned.ipynb` |

---

## 🛠️ Setup

Make sure you have Python 3.8+ and PyTorch installed. Then run:

```bash
pip install -r requirements.txt
📚 References & Inspirations
Attention Is All You Need

Language Models Are Few-Shot Learners (GPT-3)

nanoGPT

minGPT

OpenAI GPT-2 and GPT-3

✅ Status
🚀 Started on: 08 06 2025

📈 Updating daily

💬 Reach out if you'd like to learn/build together!

🙌 Acknowledgements
Thanks to the open-source community, educators, and AI researchers for making deep learning more accessible for all.