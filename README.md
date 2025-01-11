# **SkeletAge: A Skeletal Muscle Transcriptomics-Based Aging Clock**  

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![R Version](https://img.shields.io/badge/R-%3E%3D4.3.3-blue)
![Elastic Net Regression](https://img.shields.io/badge/ElasticNet-%E2%9C%94-green)  

SkeletAge is an aging clock designed to predict biological age using transcriptomic data from skeletal muscle tissue. Its main goal is identifying the **ageprint**—a tissue-specific set of genes that regulate baseline healthy aging.  

---

## 🌟 **Key Features**  

- **High Accuracy**:  
  - **Training Set**: Correlation 0.96, Mean Absolute Error (MAE) 6.55 years  
  - **Validation Set**: Correlation 0.91, MAE 6.62 years  
- **Gene Discovery**:  
  - Identifies **128 genes** critical to skeletal muscle aging  
  - Discovers **26 novel aging targets**  
- **Tissue Specificity**:  
  - Focused exclusively on skeletal muscle RNA-seq data from healthy individuals  
- **Drug Discovery Potential**:  
  - Links **23 genes** to druggable targets  
  - Highlights **9 genes** associated with approved drugs, including 4 already studied for aging  

---

## 📂 **Repository Contents**  

- **`skeletome/`**: Preprocessed RNA-seq data and Skeletome database  
- **`code/`**: R scripts for preprocessing, modeling, and age prediction  
- **`manuscripts/`**: Methodology, dataset details, and performance metrics  

---

## 🧬 **Skeletome Database**  

SkeletAge was developed using **Skeletome**, a comprehensive database of 534 skeletal muscle RNA-seq samples. Skeletome contains:  
- Raw counts aligned to **GRCh38**  
- Metadata with accurate age labels  
- Samples from 19 to 90 years of age across 11 studies  

---

