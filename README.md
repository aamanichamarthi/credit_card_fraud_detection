# 💳 Credit Card Fraud Detection
This project focuses on detecting fraudulent credit card transactions using machine learning and data analysis techniques. It utilizes a publicly available dataset with anonymized features related to transactions made by European cardholders.

# 📁 Project Structure
credit_card_fraud_detection.ipynb – Jupyter notebook containing data analysis, preprocessing, model training, and evaluation.

creditcard.csv – Dataset containing transaction records including the target label Class (1 = fraud, 0 = legitimate).

# 📊 Dataset Overview
Source: Kaggle Credit Card Fraud Detection Dataset

Observations: 284,807 transactions

Fraudulent Transactions: 492 (≈0.172%)

Features:

30 numerical features (V1–V28 are PCA-transformed for privacy)

Time, Amount, and Class (target)

# 🧠 Key Tasks Performed
✅ Data Exploration
Analyzed the distribution of legitimate vs. fraudulent transactions

Explored statistical differences in Amount and Time for fraud detection

✅ Data Visualization
Correlation heatmap to understand relationships among features

Histogram and density plots to visualize distributions

✅ Data Preprocessing
Handled class imbalance via undersampling

Feature-target split (X and Y)

✅ Model Building
Applied multiple classifiers such as:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

Used sklearn for model training, cross-validation, and evaluation

✅ Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC-AUC Curve

# 🧰 Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn


# ⚠️ Limitations
The dataset is highly imbalanced (fraud cases < 0.2%)

Undersampling may discard valuable data and affect generalizability

Real-world deployment would require continuous data ingestion and more robust modeling
