# 🚢 Titanic Survival Prediction

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-green.svg)](https://scikit-learn.org/)

**🇬🇧 English | [🇹🇷 Türkçe](README.md)**

---

## 📋 About

This project predicts the survival of RMS Titanic passengers (1912) using **Logistic Regression** and **K-Nearest Neighbors (kNN)** machine learning algorithms.

<p align="center">
  <img width="640" height="640" alt="D" src="https://github.com/user-attachments/assets/d74bf9cc-21a4-4d0a-91bc-101eb9122e18" />
</p>

## 🎯 Topics Covered

- ✅ Data Exploration & Train-Test Split
- ✅ Outlier Detection and Removal (IQR Method)
- ✅ Feature Scaling (StandardScaler)
- ✅ Logistic Regression Classification
- ✅ kNN Classification & Hyperparameter Tuning
- ✅ Model Comparison and Evaluation

## 🛠 Technologies

- **Python 3.8+**
- **NumPy, Pandas** - Data manipulation
- **Matplotlib, Seaborn** - Visualization
- **Scikit-learn** - Machine learning

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/Semihkulekcioglu/titanic_survival_ml-Titanik_hayatta_kalanlar.git
cd titanic_survival_ml-Titanik_hayatta_kalanlar

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Titanic_Hayatta_Kalma_Tahmini.ipynb
```

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80% |
| kNN (optimal k) | ~78% |

## 🔍 Key Findings

| Factor | Impact |
|--------|--------|
| **Gender** | Women had significantly higher survival rates |
| **Ticket Class** | 1st class passengers survived more than 3rd class |
| **Age** | Children and young adults had better chances |
| **Fare** | Higher fare correlated with higher survival |

## 📁 Project Structure

```
├── Titanic_Hayatta_Kalma_Tahmini.ipynb  # Main notebook
├── README.md                            # Turkish documentation
├── README_EN.md                         # English documentation
├── requirements.txt                     # Dependencies
├── .gitignore                          # Git ignore rules
└── LICENSE                             # MIT License
```

## 📝 License

MIT License - See [LICENSE](LICENSE) for details.

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>

