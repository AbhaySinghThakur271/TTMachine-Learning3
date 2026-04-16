# 📦 Food Delivery Time Prediction using Naive Bayes (GaussianNB),K-Nearest Neighbors (KNN), Decision Tree Classifier

## 📌 Project Overview

This project aims to predict whether a food delivery will be **Fast** or **Delayed** using machine learning techniques. The problem is formulated as a **binary classification task** based on factors like distance, weather conditions, traffic, and delivery details.

---

## 🎯 Objective

* Predict delivery status: **Fast (0)** or **Delayed (1)**
* Compare multiple machine learning models
* Provide actionable insights to improve delivery efficiency

---

## 🧠 Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📂 Dataset

The dataset contains features such as:

* Restaurant & Customer Location (Latitude, Longitude)
* Weather Conditions
* Traffic Conditions
* Vehicle Type
* Delivery Time

---

## ⚙️ Project Workflow

### **1. Data Preprocessing**

* Handled missing values
* Encoded categorical variables using LabelEncoder
* Normalized numerical features using StandardScaler

### **2. Feature Engineering**

* Calculated distance using **Haversine Formula**
* Created target variable:

  * `0 → Fast`
  * `1 → Delayed`

### **3. Model Building**

Implemented three models:

* Naive Bayes (GaussianNB)
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

### **4. Model Evaluation**

Used the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve

---

## 📊 Results

| Model         | Accuracy | Precision | Recall   | F1 Score |
| ------------- | -------- | --------- | -------- | -------- |
| Naive Bayes   | ~75%     | Moderate  | Moderate | Moderate |
| KNN           | ~80%     | Good      | Good     | Good     |
| Decision Tree | ~85%     | High      | High     | High     |

✅ **Best Model:** Decision Tree

---

## 🔍 Key Insights

* Distance is the most important factor affecting delivery time
* Traffic significantly increases delays
* Weather conditions impact delivery performance
* Decision Tree performed best due to handling complex relationships

---

## 💡 Recommendations

* Optimize routes using real-time traffic data
* Use predictive models to estimate delays
* Assign deliveries based on vehicle type and distance
* Integrate weather and traffic APIs

---

## 🚀 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Add real-time tracking data
* Deploy as a web app or dashboard

---

## 📁 Project Structure

```
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Time_Prediction.csv
├── Food_Delivery_Time_Prediction.ipynb
├── README.md
└── images/
```

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/food-delivery-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

## 📌 Conclusion

This project demonstrates how machine learning can improve delivery systems by predicting delays in advance. The **Decision Tree model** achieved the best performance and is recommended for deployment.

---
