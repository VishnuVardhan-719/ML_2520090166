# Machine Learning Laboratory (`ML_2520090166`)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](#experiments-index)

Curated repository containing lab experiments and practical implementations for the **Machine Learning** course. Experiments focus on end-to-end data science and machine learning workflows—ranging from exploratory data analysis and data preprocessing pipelines to classification models, regularization techniques, and decision trees using a student placement dataset (~50k records).

---

## 📁 Repository Structure

```text
ML_2520090166/
│
├── Experiments/
│   ├── EXP_01.ipynb       # Experiment 1: Dataset Inspection & Profiling
│   ├── EXP_02.ipynb       # Experiment 2: Exploratory Data Analysis (EDA) & Report
│   ├── EXP_04.ipynb       # Experiment 4: Preprocessing & Column Transformer Pipeline
│   ├── EXP_05.ipynb       # Experiment 5: Binary & Multi-class Logistic Regression
│   ├── EXP_06.ipynb       # Experiment 6: Regularization (L1, L2, ElasticNet) & Shrinkage Paths
│   └── EXP_07.ipynb       # Experiment 7: Decision Tree Classification & Visualization
│
├── ML Python  Codes/
│   └── ML_python_codes.ipynb  # Core Python programming & foundational exercises
│
└── README.md
```

---

## 🧪 Experiments Index

| # | Notebook | Topic | Description | Colab Link |
|---|---|---|---|:---:|
| **01** | [`EXP_01.ipynb`](Experiments/EXP_01.ipynb) | Dataset Inspection & Profiling | Basic data exploration, checking dimensions, missing values, duplicates, and class balance on `PlacementStatus`. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_01.ipynb) |
| **02** | [`EXP_02.ipynb`](Experiments/EXP_02.ipynb) | Exploratory Data Analysis (EDA) | Visualizing distributions across academic features (CGPA, SGPA), stream-wise placement rates, correlation matrices, and automated PDF export (`EDA_Report.pdf`). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_02.ipynb) |
| **04** | [`EXP_04.ipynb`](Experiments/EXP_04.ipynb) | Data Preprocessing Pipeline | Building scikit-learn `Pipeline` and `ColumnTransformer` for categorical encoding (`OneHotEncoder`), feature scaling (`StandardScaler`), and median imputation (`SimpleImputer`). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_04.ipynb) |
| **05** | [`EXP_05.ipynb`](Experiments/EXP_05.ipynb) | Logistic Regression | Training and benchmarking binary classification (`PlacementStatus`) and multi-class classification (`CGPA_Tier`), analyzing model coefficients and classification metrics. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_05.ipynb) |
| **06** | [`EXP_06.ipynb`](Experiments/EXP_06.ipynb) | Regularization & Hyperparameters | Evaluating Lasso ($L_1$), Ridge ($L_2$), and ElasticNet penalties across varying regularizer strengths ($C$), shrinkage paths, and hyperparameter tuning. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_06.ipynb) |
| **07** | [`EXP_07.ipynb`](Experiments/EXP_07.ipynb) | Decision Tree Classifier | Training a decision tree classifier (`max_depth=4`) for placement prediction, evaluating performance metrics, and exporting the decision tree diagram (`decision_tree.png`). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishnuVardhan-719/ML_2520090166/blob/main/Experiments/EXP_07.ipynb) |

---

## 📊 Dataset Details

The primary dataset used across experiments is the **Student Placement Prediction Dataset** (`placement_predict_50k`):
- **Samples:** ~50,000 student records
- **Academic Features:** `SGPA_Sem1` to `SGPA_Sem8`, `CGPA`, `AttendancePercent`, `HistoryOfBacklogs`
- **Skill & Co-Curricular Features:** `Internships`, `Projects`, `Workshops`, `Certifications`, `Publications`, `AptitudeTestScore`, `CodingTestScore`, `MockInterviewScore`, `SoftSkillsRating`
- **Demographics / Institutional:** `Gender`, `City`, `CollegeTier`, `Stream`, `Specialisation`, `Hostel`
- **Target Variables:**
  - `PlacementStatus`: Binary target (`Placed` vs `Not Placed`)
  - `CGPA_Tier`: Multi-class academic performance categorization

---

## 🛠️ Tech Stack & Tools

- **Language:** Python 3.8+
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (`Pipeline`, `ColumnTransformer`, `LogisticRegression`, `DecisionTreeClassifier`, metrics)
- **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/VishnuVardhan-719/ML_2520090166.git
cd ML_2520090166
```

### 2. Set Up Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
Navigate to the `Experiments/` directory and open any notebook.

Alternatively, click the **Open in Colab** badges in the table above to run notebooks directly in your browser without local setup.

---

## 👤 Author

- **Vishnu Vardhan** - [@VishnuVardhan-719](https://github.com/VishnuVardhan-719)
