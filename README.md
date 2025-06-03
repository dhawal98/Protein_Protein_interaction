# Protein-Protein Interaction Prediction

This repository contains a Jupyter Notebook for predicting Protein–Protein Interactions (PPIs) using sequence-based features and classical machine learning methods.

## 📁 Folder Structure

- `data/` – Contains raw FASTA datasets such as `human_ParkMarcotte.fasta`.
- `features/` – Stores extracted features (e.g., k-gram features).
- `models/` – (Optional) For storing trained models.
- `results/` – (Optional) For saving evaluation metrics and output.
- `new_for_next.ipynb` – Main notebook for parsing, feature extraction, training, and evaluation.

## 🧬 Dataset

The dataset used in this project is based on **Park & Marcotte**'s benchmark PPI dataset.  
It contains human protein sequences in FASTA format.

📥 Demo Download Link:  
[https://figshare.com/articles/dataset/Untitled_Item/12462509?file=23080184](for sequence dataset)
[https://www.uniprot.org/uniprotkb?query=Human](for download park-marcotte-dataset.fasta dataset)
## 🔍 What the Notebook Does

- Parses FASTA files and extracts protein sequences.
- Uses 2-gram encoding to convert sequences into numeric feature vectors.
- Trains various classical machine learning classifiers (e.g., SVM, Random Forest).
- Evaluates models using metrics like Accuracy, F1-score, and AUC.

## ⚙️ Requirements

Install dependencies with:
```bash
pip install biopython scikit-learn pandas numpy matplotlib
