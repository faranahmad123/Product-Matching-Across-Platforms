# Product Matching Across Platforms using Siamese Networks

[![Watch Demo](https://img.shields.io/badge/Watch-Demo_Video-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/faran02_nlp-ai-productmatching-activity-7405004703287246849-QbcG)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect-Faran_Ahmad-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/faran02)

## 📌 Project Overview
To build a high-accuracy real-time matcher, I implemented and evaluated multiple deep learning pipelines powered by three embedding techniques: **Word2Vec, FastText, and GloVe**.

Using a **Siamese Twin Network architecture**, I benchmarked how each embedding captures semantic similarity between product pairs, enabling cross-platform matching for platforms like Amazon, eBay, and others.

## 🚀 Key Technical Milestones

### 1. Twin Network Architecture
* Designed and trained a Siamese model to learn semantic similarity between product descriptions.
* Enabled effective cross-platform matching even when product titles or descriptions vary slightly across e-commerce sites.

### 2. Embedding Benchmarks
I evaluated three major embedding techniques for robustness, generalization, and real-time vector quality.
* **Word2Vec:** Achieved the best performance (**F1-score: 0.9540**, **AUC: 0.9920**).
* **FastText & GloVe:** Evaluated for comparison and specific use-cases.

### 3. Production-Ready Outputs
The pipeline generates trained models and embedding vectors capable of:
* ✅ Real-time similarity scoring
* ✅ Cross-platform product comparison
* ✅ Text-based product search
* ✅ Matching of unseen/new product descriptions

---

## 📂 Repository Structure

```text
Product-Matching-Across-Platforms/
│── README.md
│── requirements.txt
│── Product_Matching.ipynb    ← Main Kaggle notebook for training & inference
│
├── models/                   ← Saved models (.h5/.keras) and .npy weights
├── outputs/                  ← Performance plots & summary CSVs
└── embeddings/               ← (See "Download Data" section below)
