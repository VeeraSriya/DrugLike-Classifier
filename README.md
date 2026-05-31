# 🧪 Drug-Like Classifier (QSAR Project)

## 📌 Overview
This project predicts whether a molecule is drug-like or not using molecular descriptors and machine learning.

## ⚙️ Workflow
- Molecules collected from PubChem
- Descriptors calculated using RDKit
- Drug-likeness labeled using Lipinski Rule of Five
- Random Forest Classifier trained on molecular features

## 🧬 Features Used
- Molecular Weight (MW)
- Topological Polar Surface Area (TPSA)
- Hydrogen Bond Donors (HBD)
- Hydrogen Bond Acceptors (HBA)
- LogP

## 🤖 Model
- Random Forest Classifier
- Accuracy evaluated using confusion matrix and classification report

## 📊 Result
- Accuracy: ~1.0 (on small dataset)

## 📁 Files
- DrugLike_Classifier.ipynb
- druglike_dataset.csv

## 🚀 Tools Used
- Python
- RDKit
- PubChemPy
- Scikit-learn
- Pandas

## 📚 Learning Outcome
Understanding QSAR modeling, molecular descriptors, and basic ML classification in cheminformatics.
