# Sales Prediction Using Logistic Regression

A machine learning project that predicts whether a customer will purchase a product based on their **Age** and **Estimated Salary**, using a Logistic Regression classification model built with scikit-learn.

## 📌 Overview
This project uses the **Social Network Ads** dataset to train a binary classifier that predicts customer purchase behavior. It covers the full ML workflow — data preprocessing, feature scaling, model training, evaluation, and visualization of the decision boundary.

## 🛠️ Tech Stack
- Python
- pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

## 📊 Dataset
- **Features:** Age, Estimated Salary
- **Target:** Purchased (0 = No, 1 = Yes)
- Source: [Social Network Ads Dataset](https://www.kaggle.com/) (Kaggle)

## ⚙️ Workflow
1. Data loading and preprocessing
2. Train/test split
3. Feature scaling (StandardScaler)
4. Model training (Logistic Regression)
5. Prediction on new customer input
6. Evaluation — Confusion Matrix, Accuracy, Precision, Recall, F1 Score
7. Visualization — scatter plot and decision boundary

## 📈 Results
- **Accuracy:** 89.0%
- **Precision:** 88.88888888888889%
- **Recall:** 75.0%
- **F1 Score:** 81.35593220338984%

## 🖼️ Visualizations

### Customer Data Distribution
![Customer Data Plot](customer_data_plot.png)
*Scatter plot of Age vs Estimated Salary, colored by purchase outcome.*

### Model Evaluation
![Confusion Matrix](confusion_matrix.png)
*Confusion matrix showing the model's prediction accuracy on the test set.*

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
```
3. Open `Sales_Prediction.ipynb` in Jupyter Notebook and run all cells

## 👤 Author
Nazma Begum — [GitHub](https://github.com/Nijhumtara)
