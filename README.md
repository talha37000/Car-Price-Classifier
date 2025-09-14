
---

## 2️⃣ Car-Price-Classifier (`CLASSIFICATION_PROJECT`)
```markdown
# 🚗 Car Price Classifier

This project is a **classification machine learning model** that predicts whether the given **price of a car is acceptable or not** based on various features.

---

## 📊 Dataset
- **Dataset**: Car Evaluation & Adult dataset (preprocessed versions included).  
- **Files**:  
  - `car.data`, `car.names`  
  - `adult.data`, `adult.test`  

---

## 🧠 Machine Learning Models Used
Trained and compared multiple classifiers:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## ✅ Best Model
- After evaluation, the **best performing model** was saved as:
  - `best_model.pkl` (trained classifier)  
  - `encoder_top5.pkl`, `encoders.pkl`, `label_encoder.pkl` (encoders for features)  
  - `selected_features.pkl` (feature selection)

---

## 🚀 Features
- Input car attributes (buying price, maintenance, doors, persons, safety, etc.).  
- Predict whether the **price is acceptable** (`good/bad`).  
- GUI / Notebook-based interactive prediction.  

---

## ▶️ How to Run
```bash
# Clone repo
git clone https://github.com/talha37000/Car-Price-Classifier.git
cd Car-Price-Classifier

# Open Jupyter Notebook
jupyter notebook CLASSIFICATION_PROJECT.ipynb

📌 Future Improvements

Build a Tkinter/Web app for real-time predictions.

Expand dataset for better accuracy.

Add visualization dashboards.

👤 Author

Muhammad Talha Mubeen
🎓 BSCS - Batch 2k21
📧 [muhammadtalhamubeen37@gmail.com]
