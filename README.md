# 🐢 Predicting Turtle Nesting Trends Using Artificial Neural Network (ANN)

This project builds and evaluates an **Artificial Neural Network (ANN)** deep learning model to predict sea turtle nesting trends based on environmental and physical features. The goal is to support smarter conservation planning by accurately forecasting nesting activity.
Developed as part of the **MDA 3053 Machine Learning** coursework at **Universiti Malaysia Terengganu (UMT)**.

---

## 📌 Project Overview
* **Domain:** Environmental Data Science & Conservation Tech.
* **Dataset Source:** SEATRU (Sea Turtle Research Unit), Universiti Malaysia Terengganu
* **Dataset Size:** 656 samples (12 raw features, 7 selected features)
* **Target Variable:** `Nest`
* **Key Features:** Species, Nested status, Num eggs, Length, Width
* **Methodology:** Multi-layer ANN (ReLU activation, Backpropagation, Adam optimizer)
* **Libraries:** Python, TensorFlow/Keras, NumPy, Pandas, Seaborn, Matplotlib

---

## 🎯 Objectives
1. Assess the performance of the ANN model in predicting sea turtle nesting trends.
2. Evaluate accuracy and error metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Coefficient of Determination ($R^2$).
3. Identify potential areas for model improvement and environmental data analysis.

---

## 🏗️ Neural Network Architecture
* **Input Layer:** Normalized features (z-score scaling)
* **Hidden Layers:** 3 Hidden Layers (ReLU Activation)
* **Output Layer:** 1 Output Layer (Nest Count prediction)
* **Optimization:** Backpropagation with Adam Optimizer

---

## 📊 Model Evaluation Results
* **$R^2$ Score:** **0.992** (Captures ~99.2% of total variance in nesting counts)
* **MSE:** 0.018
* **RMSE:** 0.135
* **MAE:** 0.059
* **MAPE:** 16.816%

> **Conclusion:** The loss curves show excellent convergence without overfitting, confirming high generalization accuracy for real-world conservation tracking.
