# Microbiota-18S-DataScience
Data science notebooks for analyzing 18S rRNA eukaryotic microbiota using PR² and bioinformatics tools

**Reproducible analysis of eukaryotic microbiota (18S rRNA) in environmental and human samples using data science and bioinformatics tools.**

This repository contains Jupyter notebooks, processed data, and scripts used to analyze the composition and diversity of eukaryotic communities (mainly protozoa) based on 18S rRNA gene sequences obtained from river water, human feces, and *Crassostrea virginica* (oyster) samples collected in Chachalacas, Veracruz, Mexico.

---

## 📌 Objectives

- Process 18S rRNA sequences using **Mothur** and the **PR²** database.
- Calculate alpha and beta diversity indices.
- Identify dominant eukaryotic phyla and genera.
- Detect potentially pathogenic genera.
- Visualize results through plots and statistical analysis in Python.

---

## 🧰 Tools and Versions Used

| Tool              | Version     |
|-------------------|-------------|
| Mothur            | 1.48.0      |
| PR² database      | v5.0        |
| Python            | 3.10        |
| Jupyter Notebooks | Anaconda    |
| Pandas            | 2.0         |
| Seaborn / Matplotlib | ✔️       |
| Scikit-learn      | ✔️          |

---

## 📁 Repository Structure
Microbiota-18S-DataScience/
├── notebooks/ # Jupyter notebooks organized by analysis step
├── data/
│ ├── raw/ # Raw data (not included due to privacy)
│ └── processed/ # Abundance tables, taxonomy and diversity data
├── scripts/ # Auxiliary functions (if any)
├── figures/ # Generated visualizations
├── README.md # This file
└── LICENSE # MIT License

