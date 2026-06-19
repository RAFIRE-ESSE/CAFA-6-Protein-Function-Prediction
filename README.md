# 🧬 CAFA 6 — Protein Function Prediction

![Bioinformatics](https://img.shields.io/badge/-Bioinformatics-1a1b26?style=flat-square&logoColor=c0caf5) ![Protein Sequences](https://img.shields.io/badge/-Protein%20Sequences-1a1b26?style=flat-square&logoColor=c0caf5) ![Multi-Label Classification](https://img.shields.io/badge/-Multi-Label%20Classification-1a1b26?style=flat-square&logoColor=c0caf5) ![ESM Embeddings](https://img.shields.io/badge/-ESM%20Embeddings-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `CAFA Consortium`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/cafa-6)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/cafa-6/data)  
> **Domain:** `Bioinformatics & Protein Function`

## 📖 Overview

My work on predicting protein functions from their amino acid sequences. It's a bio-informatics challenge where we submit gene ontology predictions based on protein sequence embeddings.

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Preprocessing & EDA
*Data cleaning, feature engineering, and exploratory data analysis.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📄 [CNN_Preprocessing](./Preprocessing%20%26%20EDA/CNN_Preprocessing.ipynb) | Single Notebook | `v1` | `7 KB` | `Pandas Data Prep` |
| 📄 [Preprocessing](./Preprocessing%20%26%20EDA/Preprocessing.ipynb) | Single Notebook | `v1` | `4 KB` | `Pandas Data Prep` |
| 📁 **Preprocessing_2** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/Preprocessing_2/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/Preprocessing_2/v2.ipynb) | `Avg 77 KB` | `Pandas Data Prep` |

### 📂 Training
*Model training and tuning scripts.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **LSTM_CNN_Training** | Multi-Version Script | [v1](./Training/LSTM_CNN_Training/v1.ipynb), [v2](./Training/LSTM_CNN_Training/v2.ipynb) | `Avg 108 KB` | `PyTorch` |
| 📄 [ProtBert_Training](./Training/ProtBert_Training.ipynb) | Single Notebook | `v1` | `148 KB` | `PyTorch` |
| 📁 **ProtBert_Training_2** | Multi-Version Script | [v1](./Training/ProtBert_Training_2/v1.ipynb), [v2](./Training/ProtBert_Training_2/v2.ipynb), [v3](./Training/ProtBert_Training_2/v3.ipynb), [v4](./Training/ProtBert_Training_2/v4.ipynb) | `Avg 108 KB` | `PyTorch` |
| 📁 **ProtBert_Training_3** | Multi-Version Script | [v1](./Training/ProtBert_Training_3/v1.ipynb), [v2](./Training/ProtBert_Training_3/v2.ipynb), [v3](./Training/ProtBert_Training_3/v3.ipynb), [v4](./Training/ProtBert_Training_3/v4.ipynb), [v5](./Training/ProtBert_Training_3/v5.ipynb), [v6](./Training/ProtBert_Training_3/v6.ipynb), [v7](./Training/ProtBert_Training_3/v7.ipynb) | `Avg 180 KB` | `PyTorch` |

### 📂 Inference & Submission
*Prediction pipeline and Kaggle submission file generation.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **CNN_ProtBert_Inference** | Multi-Version Script | [v1](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v1.ipynb), [v10](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v10.ipynb), [v11](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v11.ipynb), [v12](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v12.ipynb), [v13](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v13.ipynb), [v14](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v14.ipynb), [v15](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v15.ipynb), [v16](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v16.ipynb), [v17](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v17.ipynb), [v18](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v18.ipynb), [v19](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v19.ipynb), [v2](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v2.ipynb), [v20](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v20.ipynb), [v3](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v3.ipynb), [v4](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v4.ipynb), [v5](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v5.ipynb), [v6](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v6.ipynb), [v7](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v7.ipynb), [v8](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v8.ipynb), [v9](./Inference%20%26%20Submission/CNN_ProtBert_Inference/v9.ipynb) | `Avg 119 KB` | `PyTorch` |
| 📄 [ProtBert_Inference](./Inference%20%26%20Submission/ProtBert_Inference.ipynb) | Single Notebook | `v1` | `157 KB` | `PyTorch` |

### 📂 Models & Utilities
*Shared model architectures, helper functions, and custom loss functions.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **Utility** | Multi-Version Script | [v1](./Models%20%26%20Utilities/Utility/v1.ipynb), [v2](./Models%20%26%20Utilities/Utility/v2.ipynb) | `Avg 115 KB` | `PyTorch` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"The code of life is a dark labyrinth, where every secret solved reveals ten more doors."*
>
> — **Vigneshwaran S**
