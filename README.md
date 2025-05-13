# WSI-P2P - The manuscript is under review at *****. All the relevant information will be available for future research work to promote advancements in the field, foster collaboration among researchers, and enhance our understanding of the subject matter.

# Multiple Instance Learning (MIL) for Histopathology Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.10%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the official implementation of the paper:  
**"Comparative Study of MIL Aggregators for Ovarian Cancer Subtype Classification"**  
*[Authors]*, *[Conference/Journal]*, *[Year]*  

## 🚀 Key Features
- **Comparative analysis** of MIL aggregators (Mean/Max/LSE/Attention/K-Top) on histopathology data
- **Novel K-Top pooling** for sparse tumor detection
- **Reproducible benchmarks** on TCGA & in-house datasets
- **Attention visualization** tools for interpretability

## 📦 Installation
```bash
git clone https://github.com/yourusername/MIL-Comparative-Study.git
cd MIL-Comparative-Study
conda env create -f environment.yml  # Python 3.8 + PyTorch 1.10
conda activate mil-study
