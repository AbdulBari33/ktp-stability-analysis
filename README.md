# Accelerated Stability Study — Data Analysis
**KTP Associate Pre-Interview Task | Pharmaceutical Formulation Comparison**

This repository contains a Jupyter notebook analysing an accelerated stability dataset for two prototype pharmaceutical formulations (Lot A014 and Lot B025). The analysis addresses six questions set by the development team, covering data quality, degradation trends, formulation comparison, kinetic modelling, and study limitations.

---

## Repository Contents

| File | Description |
|---|---|
| `stability_analysis.ipynb` | Main Jupyter notebook with all code, plots, and commentary |
| `requirements.txt` | Python dependencies |
| `README.md` | This file |

> **Note:** The raw data file (`KTP_task_datasets.xls`) is **not** included per the submission instructions. Place it in the same directory as the notebook before running.

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/ktp-stability-analysis.git
cd ktp-stability-analysis
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add the dataset
Place `KTP_task_datasets.xls` in the root of the repository (same folder as the notebook). This file is not tracked in version control.

### 5. Launch Jupyter and run
```bash
jupyter notebook stability_analysis.ipynb
```
Run all cells top to bottom (**Kernel → Restart & Run All**).

---

## Analysis Overview

| Section | Content |
|---|---|
| **1. Dataset Overview** | Structure, data quality, duplicate reproducibility |
| **2. Exploratory Insights** | Assay trends, impurity growth, correlation analysis |
| **3. Degradation Factors** | Effect of temperature, humidity, and time via regression |
| **4. Formulation Comparison** | Side-by-side comparison with paired statistical tests |
| **5. Modelling** | Arrhenius kinetic model + linear mixed-effects model |
| **6. Limitations** | Study weaknesses and recommendations for future work |

---

## Dependencies

- Python ≥ 3.9
- pandas, numpy, scipy, matplotlib, seaborn, statsmodels, scikit-learn, xlrd, jupyter

See `requirements.txt` for pinned versions.

---

## Contact
Submitted as part of the KTP Associate application (Ref: 43006).
