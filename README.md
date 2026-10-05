# travel-package-purchase-predictor
# ✈️ Travel Package Purchase Predictor

> Which customers are most likely to buy your next travel package? A machine learning project that finds out.

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

## 🌍 Overview
Travel companies spend heavily on pitching packages to customers who never buy.
This project predicts whether a customer will purchase a package (`ProdTaken`)
from their demographics, trip history, and sales-interaction data, so marketing
and sales teams can focus on the leads that matter.

## 🧠 What's Inside
- **Data cleaning:** fixed inconsistent labels (e.g. `Fe Male` → `Female`) and filled missing values with the median or mode
- **Feature engineering:** combined adults and children into a single `TotalVisiting` feature
- **Preprocessing:** label encoding, z-score outlier removal (|z| < 3), and standard scaling
- **Modeling:** Decision Tree Classifier, tuned with `GridSearchCV` (criterion, max depth, min samples split)
- **Evaluation:** accuracy, confusion matrix, and classification report

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | _add your score_ |
| Precision / Recall (class 1) | _add your score_ |

## 🛠️ Tech Stack
`Python` · `Pandas` · `NumPy` · `Seaborn` · `SciPy` · `scikit-learn`

## 🚀 Getting Started
```bash
git clone https://github.com/<aryank2074-ai>/travel-package-purchase-predictor.git
cd travel-package-purchase-predictor
pip install pandas numpy seaborn scipy scikit-learn jupyter
jupyter notebook travel.ipynb
```
Place `travel.csv` in the project root before running.

## 📁 Structure
```
├── travel.ipynb   # End-to-end analysis and model
├── travel.csv     # Dataset
└── README.md
```

## 🔮 Future Improvements
- Try Random Forest, XGBoost, and Logistic Regression for comparison
- Handle class imbalance (SMOTE or class weights)
- Add feature-importance plots and EDA visuals
- Deploy as a simple Streamlit app

## 🤝 Contributing
Suggestions and pull requests are welcome!

## 📄 License
MIT
