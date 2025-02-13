# Risk Analytics - Credit Risk Classification

![Risk Analytics](https://img.shields.io/badge/Built%20With-Python-blue)
![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest%20%7C%20Decision%20Tree-green)

## 🚀 Overview
This project focuses on risk analytics, particularly credit risk classification, using machine learning models such as Random Forest and Decision Tree. The dataset used is **German Credit Data**, and the goal is to predict the likelihood of a customer defaulting on a loan.

## ✨ Features
- **Credit Risk Classification**: Predict loan default risk.
- **Machine Learning Models**: Implementation of Random Forest and Decision Tree classifiers.
- **Performance Evaluation**: High accuracy (99.33%) using precision, recall, and f1-score metrics.
- **Data Preprocessing & Feature Engineering**: Handling missing values, encoding categorical data, and scaling.

## 📦 Installation
Ensure you have Python 3.8+ installed, then follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/risk-analytics.git
   cd risk-analytics
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Download the dataset (`german_credit_data.xls`) and place it in the project directory.

## 🚀 Running the Model
To train and evaluate the model, run:
```bash
python risk_analysis.py
```
This will preprocess the data, train the models, and generate classification reports.

## 📊 Results
### Random Forest Accuracy: **99.33%**
```
              precision    recall  f1-score   support

       False       0.99      1.00      0.99       145
        True       1.00      0.99      0.99       155

    accuracy                           0.99       300
   macro avg       0.99      0.99      0.99       300
weighted avg       0.99      0.99      0.99       300
```

### Decision Tree Accuracy: **99.33%**
```
              precision    recall  f1-score   support

       False       0.99      1.00      0.99       145
        True       1.00      0.99      0.99       155

    accuracy                           0.99       300
   macro avg       0.99      0.99      0.99       300
weighted avg       0.99      0.99      0.99       300
```

## 🛠️ Technologies Used
- **Python** - Core programming language
- **Scikit-learn** - Machine learning library
- **Pandas & NumPy** - Data processing and analysis
- **Matplotlib & Seaborn** - Data visualization

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.



## 📧 Contact
For inquiries or support, contact [gowrisesharoa@gmail.com]

---
**Built with ❤️ for Risk Analytics and Machine Learning**

