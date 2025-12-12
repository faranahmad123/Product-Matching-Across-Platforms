# Product Matching Across Platforms using Siamese Networks

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

## 📥 Download Large Files

[**Click Here to Download Models & Embeddings (Google Drive)**](https://drive.google.com/drive/folders/1JXUOQTgNgaFKlc4NgFu0-oAkZqyX9FQ8?usp=drive_link)

**Installation Instructions:**
1. Download the folder from the link above.
2. Move the **`.csv` files** (e.g., `FastText_Embeddings.csv`) into the `embeddings/` folder.
3. Move the **`.npy` file** (`fasttext.model.wv.vectors_ngrams.npy`) into the `models/` folder.

---

## 📊 Performance Results

| Embedding Model | F1-Score | AUC Score | Status |
| :--- | :--- | :--- | :--- |
| **Word2Vec** | **0.9540** | **0.9920** | 🏆 **Best Model** |
| FastText | *[See Notebook]* | *[See Notebook]* | Evaluated |
| GloVe | *[See Notebook]* | *[See Notebook]* | Evaluated |

## ⚙️ Setup & Installation
1. Clone the Repository
git clone [https://github.com/faranahmad123/Product-Matching-Across-Platforms.git](https://github.com/faranahmad123/Product-Matching-Across-Platforms.git)
cd Product-Matching-Across-Platforms

2. Install Dependencies
Bash
pip install -r requirements.txt

3. Run the Notebook
Open Product_Matching.ipynb in Jupyter Notebook or Google Colab to see the training pipeline and inference examples.

## 📬 Contact
This project strengthened my skills in sequence modeling, vector-space representation, and building real-time inference pipelines.

* **Developer:** Faran Ahmad
* **LinkedIn:** [Connect with me](https://www.linkedin.com/in/faran02)
* **Live Demo:** [Watch on LinkedIn](https://www.linkedin.com/posts/faran02_nlp-ai-productmatching-activity-7405004703287246849-QbcG)

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






