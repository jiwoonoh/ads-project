# Sufficient & Necessary Explanations for Race Detection in Chest X-rays

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/) [![PyTorch](https://img.shields.io/badge/pytorch-1.9%2B-orange)](https://pytorch.org/) [![MIT License](https://img.shields.io/badge/license-MIT-green)]()

## 📖 Project Overview
This repository implements a deep-learning pipeline to:
- **Predict patient race** from chest X-rays using a DenseNet-121 backbone.
- **Audit and explain** those predictions via a unified _necessary & sufficient feature_ framework.
- **Compare** our optimized masks against standard Grad-CAM saliency maps.
- **Expose** and quantify model failures on under-represented groups.

> **Key insight:** We establish baseline performance (95% accuracy) on well-represented racial groups and derive sparse masks that isolate minimal pixel subsets, sufficient and necessary to sustain correct race classification.

---

## 🔧 Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/jiwoonoh/ads-project.git
   cd ads-project

2. **Create & activate a Conda environment**
   ```bash
   conda create -n ads-project python=3.8 -y
   conda activate ads-project

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

