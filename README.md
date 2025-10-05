# Z639 Assignment 1 — Toxic Comment Classification

**Author:** Neha Kothavade  
**Course:** Social Media Mining  
**Date:** Sept 27, 2025

## Contents
- `Neha-Kothavade-assignment1.pdf` — final report
- `Neha-Kothavade-assignment1.ipynb` — reproducible notebook
- `Neha-Kothavade-assignment1-prediction.csv` — submission file (platform_id, prediction)
- `supplemental_materials.zip` — artifacts (confusion matrices, PR curve, env versions, models)

## Reproducibility
1. Open the notebook in Jupyter/Colab and run all cells.
2. The notebook regenerates figures that appear in the report and writes the prediction CSV.
3. See `env_versions.txt` inside the supplemental zip for library versions.

## Notes
- Decision threshold chosen via F1 sweep on validation split.
- Baseline: TF-IDF + Logistic Regression. Final: Fine-tuned BERT.
