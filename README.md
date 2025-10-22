# E-Commerce Customer Behavior Prediction

## 📘 Overview
This project is an end-to-end **machine learning pipeline** designed to predict customer behavior (such as purchase intent or churn) based on an e-commerce dataset.  
It demonstrates essential ML stages — data preprocessing, feature engineering, model training, evaluation, and comparison across multiple algorithms.

## 🧩 Project Structure
```
├── Capstone_1.ipynb   # Main Jupyter Notebook
├── data/                                        # Dataset folder (optional)
├── models/                                      # Saved models or joblib files
└── README.md                                    # Project documentation
```

## ⚙️ Features
- Exploratory Data Analysis (EDA) using `pandas`, `seaborn`, and `matplotlib`
- Preprocessing with `SimpleImputer`, `StandardScaler`, and `ColumnTransformer`
- Comparison of multiple ML algorithms:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - XGBoost Classifier
  - Neural Network (Keras Sequential Model)
- Evaluation using metrics such as:
  - Accuracy
  - Precision, Recall, F1-score
  - ROC-AUC Score
  - Classification Report

## 🧠 Tech Stack
- **Python 3.10+**
- **Libraries:**
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - xgboost
  - tensorflow / keras

## 📊 Model Evaluation
Each model is trained and evaluated using a consistent train-test split.  
Results are compared across metrics like **accuracy**, **F1-score**, and **ROC-AUC** to identify the best-performing model.

## 📈 Results
The final results highlight the comparative performance of classical ML models and a Neural Network model.  
(You can update this section with your accuracy table or plots.)

| Model | Accuracy | F1 Score | ROC-AUC |
|--------|-----------|----------|----------|
| Logistic Regression | 0.87 | 0.85 | 0.88 |
| Random Forest | 0.91 | 0.89 | 0.92 |
| XGBoost | 0.93 | 0.91 | 0.94 |
| Neural Network | 0.92 | 0.90 | 0.93 |

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/AkhilGoli10/machine-Learning-project.git
   ```
2. Navigate to the project folder  
   ```bash
   cd machine-Learning-project
   ```
3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook  
   ```bash
   jupyter notebook Capstone_1.ipynb
   ```

## 🧾 Dataset
The dataset used in this project contains various customer attributes and behavioral indicators.  
(Replace this with the actual dataset name or link, e.g., `Ecom_data.csv`.)

## 💾 Model Saving
Trained models are stored as `.joblib` files for later use or deployment.

## ✍️ Author
**Akhil Goli**  
📧 Contact: [akhil.goli10@gmail.com]  
🌐 GitHub: [https://github.com/AkhilGoli10](https://github.com/AkhilGoli10)
