# Agricultural-Production-Optimization-Engine  

Agriculture relies on soil composition and climate. However, unpredictable weather events (rain, heatwaves, humidity shifts) can lead to major losses.  
This project builds a **Machine Learning model** that predicts **optimal crops** for specific soil and climate conditions, helping farmers **optimize agricultural production**.

---

## 🛠 Key Factors Considered:
1. **Soil Composition:**  
   - Nitrogen (N), Phosphorus (P), Potassium (K)  
   - pH levels  
2. **Climate Conditions:**  
   - Temperature (°C)  
   - Humidity (%)  
   - Rainfall (mm)  
3. **New Feature Added:**  
   - **Soil Type Classification** (Categorical feature added for better predictions)

---

## 🏆 Machine Learning Approach:
- **Dimensionality Reduction:** PCA is applied to reduce redundant features.
- **Classification Models Used:**
  - Logistic Regression
  - Decision Tree
  - SVM
  - Gaussian Naïve Bayes
  - K-Nearest Neighbors (KNN)
  - Bagging Classifier
  - AdaBoost
  - Gradient Boosting
  - XGBoost  

---

## 📊 PCA Implementation:
To improve efficiency, **PCA (Principal Component Analysis)** is used:
- Reduces feature dimensionality.
- Improves model performance.
- Ensures better generalization.

---

## 🔍 Updated Classification Accuracy:
| Model                         | Accuracy |
|--------------------------------|----------|
| Logistic Regression            | 0.88     |
| Decision Tree                  | 0.96     |
| SVM                             | 0.93     |
| Gaussian Naïve Bayes            | 0.99     |
| K-Nearest Neighbors             | 0.93     |
| Bagging Classifier              | 0.97     |
| AdaBoost                        | 0.17     |
| Gradient Boosting               | 0.97     |
| XGBoost                         | 0.95     |

---

## 📁 Dataset:
- Contains **22 unique crops** (e.g., Maize, Wheat, Mango, Watermelon).
- Captures soil and climate factors needed for crop growth.

---

## 📌 Libraries Used:
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn, XGBoost
- **Feature Engineering:** PCA, Label Encoding

This model aims to **revolutionize precision farming** by providing **data-driven crop recommendations**! 🚀
