# 🧾 Customer Churn Prediction using ANN  

This project implements an **Artificial Neural Network (ANN)** to predict customer churn for a credit card company. The dataset used is from Kaggle: [Credit Card Customer Churn Prediction](https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction).  

---

## 📌 Project Overview  
Customer churn is a major challenge for businesses, as retaining customers is often more cost-effective than acquiring new ones.  
This project applies **Deep Learning (ANN)** to classify whether a customer is likely to churn (leave) or stay.  

The model achieves an accuracy of **~84.6%** on the dataset.  

---

## 📂 Dataset  
- Source: Kaggle (`rjmanoj/credit-card-customer-churn-prediction`)  
- Contains customer demographics, account information, and transaction history.  
- Target variable: **Churn** (1 = Customer left, 0 = Customer stayed).  

---

## ⚙️ Tech Stack  
- **Python**  
- **TensorFlow / Keras** (for ANN model)  
- **NumPy, Pandas** (data handling)  
- **Matplotlib, Seaborn** (visualization)  
- **Scikit-learn** (data preprocessing, metrics)  

---

## 🧠 Model Architecture  
The ANN model is built using Keras Sequential API:  

1. **Input Layer** – Preprocessed features  
2. **Hidden Layer** – Dense layer with 3 neurons (ReLU activation)  
3. **Output Layer** – Dense layer with 1 neuron (Sigmoid activation for binary classification)  

### Model Summary:
```text
Layer (type)        Output Shape     Param #
-------------------------------------------------
dense_12 (Dense)    (None, 3)        36
dense_13 (Dense)    (None, 1)        4
-------------------------------------------------
Total params: 40
Trainable params: 40
Non-trainable params: 0
