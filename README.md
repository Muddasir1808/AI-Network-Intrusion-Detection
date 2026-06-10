# 🛡️ Network Intrusion Detection System (NIDS)

A machine learning project that detects network intrusions using classical AI and ML techniques on the NSL-KDD inspired dataset (6,000 records, 15 features).

---

## 📌 Overview

Network Intrusion Detection Systems (NIDS) monitor network traffic and raise alerts when suspicious activity is detected. This project applies multiple AI and ML approaches to classify network connections as **Normal (0)** or **Attack (1)**.

---

## 🗂️ Project Structure

```
AI-Network-Intrusion-Detection/
│
├── network_intrusion_detection.ipynb   # Main notebook (all 5 tasks)
├── README.md                           # This file
└── requirements.txt                    # Python dependencies
```

> **Note:** Dataset is not included. Place `network_traffic.csv` inside a `dataset/` folder before running.

---

## ✅ Tasks Implemented

| Task | Description | Accuracy |
|------|-------------|----------|
| Task 1 | Data Exploration & Visualization | — |
| Task 2 | Rule-Based Simple Reflex Agent | 80.5% |
| Task 3 | KNN Classifier (best k=1) | 95.7% |
| Task 3 | Naive Bayes Classifier | 78.7% |
| Task 3 | Logistic Regression | 91.5% |
| Task 4 | K-Means Clustering (unsupervised) | 87.0% |
| Task 5 | Genetic Algorithm for Feature Selection | 91.7% |

---

## 🔧 Technologies Used

- **Language:** Python 3.10
- **Libraries:** scikit-learn, pandas, numpy, matplotlib
- **Algorithms:** KNN, Naive Bayes, Logistic Regression, K-Means, Genetic Algorithm

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Muhammad-SE-Eng/AI-Network-Intrusion-Detection.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Place the dataset:
```
dataset/network_traffic.csv
```

4. Open and run the notebook:
```bash
jupyter notebook network_intrusion_detection.ipynb
```

Run all cells from top to bottom (**Kernel → Restart & Run All**).

---

## 📊 Key Results

- **Best Classifier:** KNN (k=1) with **95.7% accuracy**
- **Unsupervised Clustering:** K-Means recovered 87% of true class structure without labels
- **Feature Selection:** Genetic Algorithm found 13/15 optimal features with **91.7% accuracy**

---

## 👤 Author

**Muhammad Muddasir**  
Roll No: 24P-0524  
BS Computer Science — 3rd Year  
FAST National University, Hyderabad

---

## 📚 Course

**Artificial Intelligence**  
Instructor: Saad Ahmed  
FAST National University

