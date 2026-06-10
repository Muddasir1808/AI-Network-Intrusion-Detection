# Network Intrusion Detection System
**AI Semester Project**

---

## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file contains:
```
numpy>=1.24
pandas>=2.0
scikit-learn>=1.3
matplotlib>=3.7
```

---

## Folder Structure

```
AI_Project/
│
├── dataset/
│   ├── network_traffic.csv       # Dataset (provided separately)
│   └── README.md                 # Dataset description
│
├── network_intrusion_detection.ipynb   # Main notebook (all 5 tasks)
├── report.pdf                          # Project report
├── requirements.txt                    # Python dependencies
└── README.md                           # This file
```

---

## How to Run

1. Make sure the `dataset/` folder is in the same directory as the notebook.
2. Open the notebook:

```bash
jupyter notebook network_intrusion_detection.ipynb
```

3. Run all cells in order from top to bottom:
   - **Kernel → Restart & Run All**

That's it. All 5 tasks will execute and all plots will be displayed and saved automatically.

---

## Tasks Overview

| Task | Description |
|------|-------------|
| Task 1 | Data exploration — shape, describe, histograms, class distribution |
| Task 2 | Simple reflex agent — rule-based classifier |
| Task 3 | Supervised learning — KNN, Naïve Bayes, Logistic Regression |
| Task 4 | K-Means clustering + PCA visualisation |
| Task 5 | Genetic algorithm for feature selection |

---

## Notes

- The dataset is **not included** in this ZIP (as per submission guidelines).
- All random seeds are fixed at `random_state=42` for reproducibility.
- The notebook was tested on Python 3.10.
