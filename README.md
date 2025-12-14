# House Price Prediction using Gradient Boosting Regression

## 📌 Project Overview
This project focuses on predicting **real estate prices** based on housing features using a **Gradient Boosting Regressor**.  
The dataset was collected from **uybor.uz** and represents real-world housing data.

The project demonstrates a full **data science regression pipeline**, including data cleaning, feature engineering, model training, and evaluation.

---

## 🏠 Dataset
- Source: uybor.uz (real estate listings)
- Format: Excel (`.xlsx`)
- Target variable: `price`

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## 🔄 Data Preprocessing
- Removed outliers using **Interquartile Range (IQR)**
- Applied **one-hot encoding** for categorical variables
- Applied **log transformation** to the target variable to reduce skewness
- Split the data into training and testing sets (80/20)

---

## 🧠 Model
- **Gradient Boosting Regressor**
- Hyperparameters:
  - `n_estimators = 500`
  - `learning_rate = 0.05`
  - `max_depth = 4`
  - `subsample = 0.8`

---

## 🚀 Training & Evaluation
- Model trained on the training dataset
- Evaluated using:
  - **Mean Squared Error (MSE)**
  - **R² Score** (≈ 0.81)

The high R² score indicates strong predictive performance on unseen data.

---

## 📊 Visualization
- Scatter plot comparing **actual vs predicted values**
- Visual analysis used to assess prediction quality and error distribution

---

## 💡 Key Learnings
- Handling real-world noisy data using outlier removal
- Improving regression performance with log-transformed targets
- Applying ensemble learning techniques for tabular data
- Interpreting regression metrics and visual results

---

## 📂 Project Structure


---

## 👩‍💻 Author
**Vazira Holboeva**  
Data Science & AI Intern 
GitHub: https://github.com/Holboeva
