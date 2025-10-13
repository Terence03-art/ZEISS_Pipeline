# Psl Intensity Analysis — Confocal Imaging & Quantitative Comparison

This project investigates differences in Psl exopolysaccharide intensity among three *Pseudomonas aeruginosa* genotypes (WT, deletion, constitutive expression) at infection and distant tissue sites.  

---

## 🔬 Project Files

- [📄 Project Portfolio (1-page PDF summary)](https://github.com/Terence03-art/ZEISS_Pipeline/blob/main/notebooks/T_Makuvise%20MSc%20Research_Portfolio.pdf)
- [📘 Full Jupyter Notebook (code + plots)](https://github.com/Terence03-art/ZEISS_Pipeline/blob/main/notebooks/analysis%20notebook.ipynb)
- [📊 Figures directory](https://github.com/Terence03-art/ZEISS_Pipeline/tree/main/figures)

---

## 🧠 Methods Summary
- Quantified Psl intensity from confocal images using ZEISS Intellesis ML segmentation.
- Performed ANOVA and two-way RM ANOVA with post-hoc Tukey tests in Python (GraphPad-style visualisation).
- Generated correlation analyses between Psl intensity, H&E nuclei counts, and PA01 mean intensity.

---

## 💡 Tools
Python (pandas, seaborn, matplotlib, statsmodels), GraphPad Prism, R  
ZEISS Axioscan 7, ZEISS Intellesis

---

## 📈 Key Results
- Psl intensity significantly differed across genotypes (p ≤ 0.001).
- Weak correlation observed between Psl and bacterial load (r = -0.09).  
- Workflow reproducible using included notebook and data (anonymised).

---

© 2025 Terence Makuvise. For academic and professional use.


# ZEISS image metrics — reproducible notebook
Author: Terence Makuvise — MSc (Distinction)

This repo demonstrates a short reproducible analysis of ZEISS-derived metrics using anonymised data.

Contents
- `data/sample_data_anonymised.csv` — anonymised/synthetic dataset
- `notebooks/analysis_notebook.ipynb` — Jupyter notebook (EDA, plotting, simple regression)
- `figures/` — exported PNG figures

How to run
1. Clone repository
2. Create Python environment: `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter notebook` and open `notebooks/analysis_notebook.ipynb`
