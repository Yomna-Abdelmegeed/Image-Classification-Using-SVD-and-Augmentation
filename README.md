# 🧠 Image Classification Using SVD and Optimization

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2412.07288-b31b1b.svg)](https://arxiv.org/abs/2412.07288)

This repository contains the Python implementation of the research paper:

> **"Image Classification Using Singular Value Decomposition and Optimization"**  
> _by yomna abdelmegeed , nadia Ashraf , monica maged , yara ahmed , hagar atef , menna alla ahmed _

The method leverages **Singular Value Decomposition (SVD)** and **optimized categorical templates** for classifying images of **Boxer dogs** and **Persian cats**. It uses low-rank approximations and norm-based error metrics to distinguish between image categories with competitive performance.

---

## 📌 Features

- 📷 Image preprocessing & augmentation  
- 🧮 SVD-based low-rank approximation  
- 📊 Norm-based error classification (Frobenius, L1, L2)  
- 🧠 Optimized vs. Average templates comparison  
- 📈 Visualizations: error plots, confusion matrices, prediction probabilities  
- 🧪 Single image testing support

---

## 🧰 Prerequisites

- **Python**: 3.8 or higher  
- **Jupyter Notebook**: For interactive execution  
- **Dependencies**: Listed below  
- **Dataset**: Images organized in folders:
  - `boxer/` – Boxer dogs  
  - `persian_cat/` – Persian cats  
- **Hardware**: CPU is sufficient (GPU optional)

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/image-classification-svd.git
cd image-classification-svd
