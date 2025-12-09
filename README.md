# NLP Product Classification Project

This repository contains a semester project focused on classifying products into predefined categories using Natural Language Processing (NLP). Product descriptions are analyzed using deep learning models to predict their corresponding categories.

---

## 📘 Project Overview

### Objective
Predict product categories—such as **Household**, **Books**, **Clothing & Accessories**, and **Electronics**—from raw textual descriptions.

### Approach
The project applies:
- Classical NLP preprocessing,
- Deep sequence models,
- Transformer-based language models  
to accurately infer category labels from product text.

---

## 🧠 Models Implemented

### **BiLSTM**
- Effective for modeling sequences.
- Lightweight and easy to deploy.
- Fully included in the repository.

### **DeBERTa-v3-small**
- Transformer-based model providing strong performance.
- Model weights stored externally due to size limits (Google Drive link included in notebooks).

---

## ✨ Features

- Predict categories directly from raw product descriptions.
- Multiple model architectures to compare performance.
- Ready-to-use inference notebooks.
- Easily extendable to new datasets or categories.

---

## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `*.ipynb` | Training, evaluation, and inference notebooks. |
| `tokenizer/` | Tokenizer files for both BiLSTM and DeBERTa models. |
| `models/` | Pretrained BiLSTM models (DeBERTa available via Google Drive). |
| `utils/` | Helper scripts for text preprocessing and evaluation. |

---

## 🚀 Usage

### 1. Clone the repository
```bash
git clone <repository-url>
cd <repository-folder>

2. Open a notebook

Use Jupyter Notebook or Google Colab.

3. Load the required models

BiLSTM: included in the repository.

DeBERTa-v3-small: download from Google Drive and place in the correct directory.

4. Run inference

Insert new product descriptions in the notebook and execute the inference cells to get predicted categories.