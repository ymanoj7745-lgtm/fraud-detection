## 📊 Fraud Detection on Financial Transactions

This project focuses on detecting fraudulent financial transactions using machine learning techniques on a large-scale, highly imbalanced dataset (~6.6 million records).  
The objective is to build a reliable pipeline that can identify fraud while minimizing false negatives.

---

##  Project Highlights
- Worked with real-world, large-scale data
- Performed extensive feature engineering
- Handled class imbalance using appropriate evaluation metrics
- Built a reproducible ML pipeline

---

## Project Structure
fraud-detection/
│
├── eda.ipynb              # Exploratory Data Analysis & insights
├── main.ipynb             # Data preprocessing & feature engineering
├── ml_pipeline.ipynb      # Model training, evaluation & pipeline
└── README.md

---

##  Dataset
- Size: ~6.6 million rows
- Type: Financial transaction data
- Target variable: isFraud
- Note: Dataset is not included due to large file size (~473 MB)

---

## Feature Engineering
- Transaction balance difference analysis
- Origin & destination account behavior
- Log transformation for skewed features
- Time-based feature extraction
- Handling missing and infinite values

---

## 🤖 Models Used
- Logistic Regression
- Random Forest Classifier

---

## Evaluation Metrics
Due to severe class imbalance, accuracy was not relied upon.

Primary metrics:
- Recall
- ROC-AUC Score
- Confusion Matrix

---

##  Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Key Learnings
- Handling large datasets efficiently
- Importance of recall in fraud detection
- Real-world ML pipeline design
- Feature engineering impact on model performance

---

##  Future Improvements
- Hyperparameter tuning
- Model deployment using Flask/FastAPI
- Experimenting with XGBoost / LightGBM

---

⭐ If you found this project useful, feel free to star the repository!
