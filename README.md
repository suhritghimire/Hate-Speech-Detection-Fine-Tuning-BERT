# 🧠 BERT for Hate Speech Detection

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![HuggingFace](https://img.shields.io/badge/🤗-Transformers-orange)](https://huggingface.co)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Fine-tuning **BERT** (`bert-base-uncased`) for hate speech and offensive language detection. Demonstrates how a pre-trained transformer vastly outperforms classical LSTM-based approaches on the same dataset.

---

## 📊 Results

| Model | Accuracy | F1 (Weighted) |
|-------|----------|---------------|
| BERT fine-tuned | — | — |

---

## 📁 Structure

```
bert-hate-speech/
├── HateSpeech.ipynb                      # BERT fine-tuning notebook
├── Hate_Speech_Detection_Using_LSTM.ipynb # Baseline comparison
└── README.md
```

---

## 🚀 Quickstart

Open `HateSpeech.ipynb` in Google Colab:

1. Install dependencies: `pip install transformers datasets`
2. Run all cells to fine-tune BERT

---

## 📚 References

> Devlin, J., et al. (2018). *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.* [arXiv:1810.04805](https://arxiv.org/abs/1810.04805)
