# 🧠 Machine Learning Learning Journey

A personal repository documenting my hands-on exploration of core Machine Learning algorithms through Jupyter notebooks and real-world datasets.

---

## 📚 What's Inside

| Module | Notebook | Dataset | Description |
|---|---|---|---|
| `Linear_regression` | `linear_regression.ipynb` | `medical.csv` | Predicting continuous outcomes using linear models |
| `Logistic_regression` | `logistic_regression.ipynb` | `weatherAUS.csv` | Binary classification — predicting Australian rainfall |
| `Decision_Tree` | `decision_tree.ipynb` | — | Tree-based decision making and classification |
| `ML_Approach` | `approach.ipynb` | `store.csv`, `train.csv`, `test.csv` | End-to-end ML workflow: data prep, training, evaluation |

---

## 🗂️ Project Structure

```
.
├── Linear_regression/
│   ├── linear_regression.ipynb   # Notebook: Linear Regression
│   └── medical.csv               # Dataset: medical cost data
│
├── Logistic_regression/
│   ├── logistic_regression.ipynb # Notebook: Logistic Regression
│   ├── weatherAUS.csv            # Dataset: Australian weather data
│   └── aussie_rain.joblib        # Saved trained model
│
├── Decision_Tree/
│   └── decision_tree.ipynb       # Notebook: Decision Trees
│
├── ML_Approach/
│   ├── approach.ipynb            # Notebook: Full ML workflow
│   ├── store.csv                 # Dataset: store data
│   ├── train.csv                 # Training split
│   └── test.csv                  # Test split
│
└── .venv/                        # Python virtual environment
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12+
- Jupyter Notebook or JupyterLab

### Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd <repo-name>

# Activate the virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate

# Launch Jupyter
jupyter notebook
```

Then open any `.ipynb` file from the module folders and run the cells.

---

## 🛠️ Key Libraries Used

- **NumPy** — numerical computing
- **Pandas** — data manipulation and analysis
- **Scikit-learn** — ML algorithms and model evaluation
- **Matplotlib / Plotly** — data visualization
- **Joblib** — model persistence (saving/loading trained models)

---

## 📖 Topics Covered

**Linear Regression** — understanding the relationship between continuous variables, fitting a line, and evaluating with metrics like MSE and R².

**Logistic Regression** — binary classification, sigmoid function, decision boundaries, and model evaluation with accuracy, precision, and recall.

**Decision Trees** — tree construction, splitting criteria (Gini / entropy), overfitting, and pruning concepts.

**ML Approach** — structured end-to-end pipeline: exploratory data analysis (EDA), feature engineering, train/test splits, model training, and evaluation.

---

## 📝 Notes

- Each notebook is self-contained with markdown explanations alongside the code.
- The saved model (`aussie_rain.joblib`) in the Logistic Regression module lets you reload and reuse the trained classifier without retraining.
- Datasets are included directly in each module folder for easy access.

---

## 🎯 Goals

- [ ] Understand the math behind core ML algorithms
- [ ] Apply algorithms to real datasets
- [ ] Build intuition for when to use which model
- [ ] Learn to evaluate and improve model performance
- [ ] Explore more algorithms (SVM, KNN, Random Forests, Neural Networks...)

---

*Learning in public — one notebook at a time.* 🚀
