# Machine Learning for Cybersecurity
## Laboratory Repository – Machine Learning Applications in Cybersecurity

**ISCTE – Instituto Universitário de Lisboa**  
**Course:** 2025/2026  
**Professor:** João Pedro Pavia  

---

## 📚 Overview

This repository contains the laboratory assignments and practical exercises from the course **Machine Learning for Cybersecurity**.

The course focuses on applying Machine Learning techniques to real-world cybersecurity challenges, with emphasis on Intrusion Detection Systems (IDS), anomaly detection, and data-driven security analysis.

---

## 🎯 Course Objectives

- Understand the fundamentals of Machine Learning
- Apply supervised and unsupervised learning techniques
- Perform exploratory data analysis on security datasets
- Prepare and preprocess data for ML models
- Evaluate models considering false positives and false negatives
- Understand adversarial machine learning concepts

---

## 📂 Repository Structure

```
Aprendizagem_Automatica_Ciberseguranca/
├── data/              # Dataset folder (NOT included in repo)
├── notebooks/         # Jupyter notebooks (laboratory work)
├── src/               # Python scripts
├── reports/           # Lab reports (PDF)
├── requirements.txt   # Python dependencies
├── .gitignore
└── README.md
```

---

## 🐍 Environment Setup

This project requires a **local Python virtual environment (.venv)** for dependency isolation.

### Step 1: Clone the repository

```bash
git clone <repository-url>
cd Aprendizagem_Automatica_Ciberseguranca
```

### Step 2: Create virtual environment

```bash
python -m venv .venv
```

### Step 3: Install dependencies

**Windows:**

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

**macOS/Linux:**

```bash
source .venv/bin/activate
pip install -r requirements.txt
```

### Step 4: Select the correct interpreter in VS Code

1. Open Command Palette: `Ctrl + Shift + P`
2. Search for: **Python: Select Interpreter**
3. Choose: `.venv\Scripts\python.exe` (Windows) or `.venv/bin/python` (macOS/Linux)

---

## 📊 Dataset

This course uses the **NSL-KDD dataset**, a standard benchmark for network intrusion detection research.

> **⚠️ Important:** The dataset is NOT included in this repository and must be obtained separately.

### Accessing the dataset

Retrieve the dataset from:

- **Official source:** https://www.unb.ca/cic/datasets/nsl.html
- **Kaggle:** (if specified by the instructor)

### Configuration

1. Download the dataset file
2. Place it in the `data/` directory
3. Verify the filename matches the expectations specified in the notebooks

**Example:**

```
data/nsl_kdd.csv
```

---

## 🚀 Running the Notebooks

1. Open the project in VS Code
2. Open a notebook from the `notebooks/` directory
3. Select the Jupyter kernel from your local `.venv` environment
4. Execute cells in sequential order

### Verifying the environment

Execute the following Python code in any notebook to confirm the correct interpreter is active:

```python
import sys
print(sys.executable)
```

**Expected output:**

```
...\Aprendizagem_Automatica_Ciberseguranca\.venv\Scripts\python.exe
```

---

## 🧠 Laboratory Topics

Covered topics include:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Handling Categorical Features
- Feature Scaling (StandardScaler)
- Train/Test Split
- Class Imbalance Analysis
- Model Evaluation Metrics
- Intrusion Detection Modeling
- Adversarial ML Concepts

---

## 📈 Technologies Used

| Technology | Purpose |
|---|---|
| **Python 3.13** | Programming language |
| **pandas** | Data manipulation and analysis |
| **numpy** | Numerical computing |
| **scikit-learn** | Machine learning algorithms |
| **matplotlib** | Data visualization |
| **seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive notebook environment |

---

## 🔐 Important Notes

- **The `data/` directory is ignored by Git** – Do not commit dataset files
- **The `.venv/` directory is ignored by Git** – Virtual environments are not version-controlled
- **Always use the local virtual environment** to ensure consistent reproducibility across systems
- Install all dependencies from `requirements.txt` before executing any notebooks

---

## 👤 Author

**Tomás Miguel Cunha Manarte**  
Licenciatura em Desenvolvimento de Software e Aplicações  
ISCTE – Instituto Universitário de Lisboa