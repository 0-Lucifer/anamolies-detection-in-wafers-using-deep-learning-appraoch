# A Deep Fusion Approach for Wafer Map Failure Pattern Recognition

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-blue">
  <img src="https://img.shields.io/github/stars/0-Lucifer/anamolies-detection-in-wafers-using-deep-learning-appraoch?style=social">
</p>

<p align="center">
  <strong>Advanced deep learning models for automated wafer defect classification & anomaly detection</strong><br>
  Full WM-811K (LSWMD) dataset – 811,457 real wafer maps
</p>

---

## Dataset Download (~2.3 GB)

The dataset is **not committed to Git** (repo stays < 15 MB, clones instantly).

### Easy 2-Step Setup

1. **Download the dataset zip**  
   [Download dataset.zip – 2.3 GB](https://drive.google.com/drive/folders/1WxC8Cj9YJWhf2oeuccxwULKQGPIJc6-Q?usp=sharing)

2. **Extract the zip directly into the project root folder**

After extraction, your project structure will look exactly like this:

```bash
wafer-anomaly-detection/          # ← main project folder
├── dataset/
│   ├── LSWMD.pkl                     # Raw data (∼2.05 GB)
│   └── processed/                    # Preprocessed files
│       └── (your .h5 files here)
├── figures/                          # Saved plots & visualizations
├── PRWMF.ipynb                       # Main notebook
├── LICENSE
├── .gitignore
├── README.md
└── (other files you add later)
