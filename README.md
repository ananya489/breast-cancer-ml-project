# Breast Cancer Prediction using Machine Learning

This project is a Machine Learning classification model that predicts whether a breast tumor is **Malignant (Cancerous)** or **Benign (Non-cancerous)** using medical diagnostic data.

---

## 📊 Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** Kaggle / UCI Machine Learning Repository
- **Total Samples:** 569
- **Features:** 30 numerical medical features
- **Target Variable:**
  - `0` → Malignant
  - `1` → Benign

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧠 Machine Learning Workflow
1. Load and explore the dataset
2. Convert categorical target values into numerical form
3. Split data into training and testing sets
4. Apply feature scaling using StandardScaler
5. Train Logistic Regression model
6. Evaluate model using:
   - Accuracy
   - Classification Report
   - Confusion Matrix

---

## 📈 Model Used
- **Logistic Regression**
  - Suitable for binary classification
  - Fast and interpretable
  - Widely used in medical prediction systems

---

## ✅ Results
- **Accuracy Achieved:** ~98%
- The model performs well on unseen test data

---

## 📁 Project Files
- `breastcancer.ipynb` → Jupyter Notebook with full implementation
- `breast-cancer.csv` → Dataset
- `README.md` → Project documentation

---

## 🚀 How to Run the Project
1. Clone the repository or download the files
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
