# 🎓 Student Academic Outcome Prediction

<div align="left">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

### Predicting Student Academic Outcomes using Machine Learning

*A complete end-to-end machine learning pipeline for classifying students as **Dropout**, **Enrolled**, or **Graduate**.*

📅 **Completed:** April 2026

---

# 📖 Overview

Educational institutions generate vast amounts of academic data that can be leveraged to improve student success. This project develops an end-to-end machine learning pipeline capable of predicting a student's academic outcome based on demographic, socioeconomic, and academic performance indicators.

The objective is to identify students who are at risk of dropping out, allowing institutions to implement timely interventions and improve overall academic success.

---

# 🎯 Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Visualize relationships between important variables
- Apply dimensionality reduction techniques
- Perform unsupervised learning
- Train multiple machine learning models
- Compare model performance
- Interpret feature importance
- Identify the best-performing predictive model

---

# 📊 Dataset

The dataset contains information from **4,424 university students** with **36 input features** covering:

- Student demographics
- Academic history
- Admission information
- Scholarship status
- Financial information
- First semester performance
- Second semester performance

Target Classes:

- 🔴 Dropout
- 🟡 Enrolled
- 🟢 Graduate

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 🔍 Exploratory Data Analysis

The project includes:

- Class distribution analysis
- Correlation heatmaps
- Boxplots
- Violin plots
- Histograms
- Feature relationship analysis

---

# 🤖 Machine Learning Models

The following supervised learning models were implemented:

- Decision Tree
- Random Forest
- Logistic Regression

---

# 📈 Unsupervised Learning

- Principal Component Analysis (PCA)
- K-Means Clustering
- t-SNE Visualization

---

# ⚙ Model Evaluation

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Cross Validation
- GridSearchCV

---

# 🏆 Results

| Model | Accuracy |
|-------|----------:|
| Decision Tree | 65.5% |
| Logistic Regression | 73.0% |
| ⭐ Random Forest | **76.8%** |

The Random Forest classifier achieved the best overall performance, providing the highest accuracy and balanced classification across all target classes.

---

# 📂 Project Structure

```
student-academic-outcome-prediction/
│
├── Dataset/
│   └── Student Academic Outcome Prediction Data.csv
│
├── Student_Academic_Outcome_Prediction.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/subhadip191/student-academic-outcome-prediction.git
```

Move into the project

```bash
cd student-academic-outcome-prediction
```

Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📚 Academic Context

This project was completed as part of the **Statistical Learning and Data Analysis** coursework at the **University of Naples Federico II (UNINA)**.

**Course Instructor:** **Professor Roberta Siciliano**

This repository has been expanded and organized as a professional portfolio project for educational and demonstration purposes.

---

# 👨‍💻 Author

## **Subhadip Maity**

🌐 GitHub

https://github.com/subhadip191

💼 LinkedIn

https://linkedin.com/in/subhadipmaity191

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
