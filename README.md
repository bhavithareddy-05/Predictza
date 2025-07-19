# Predictza
# Enhanced Heart Disease Diagnosis through Advanced Predictive Modelling

This project presents an advanced machine learning system for diagnosing heart diseases using ECG image-derived metadata. By integrating ensemble learning techniques, the system classifies heart conditions such as *Normal, **Abnormal, **Myocardial Infarction (MI), and **History of MI*, improving diagnostic accuracy, reliability, and speed.

## 🧠 Project Objective

To design and develop a machine learning-based solution that:
- Extracts metadata from ECG images
- Utilizes ensemble learning (Random Forest, XGBoost, CatBoost)
- Classifies heart diseases with high accuracy via a Soft Voting Classifier
- Supports scalable, real-time prediction in clinical or remote settings

## 💡 Features

- 📷 ECG image metadata extraction
- 🧹 Robust preprocessing (data cleaning, label encoding)
- 🤖 Ensemble model (Random Forest, XGBoost, CatBoost)
- 📊 Multi-class classification
- 🌐 User-friendly interface via Streamlit
- 💾 Local database storage of user history & reports

## ⚙ System Architecture

1. Upload ECG image via web interface
2. Extract features (ST elevation, Q wave, T wave inversion, QRS complex)
3. Pass metadata to trained models
4. Soft Voting Classifier consolidates predictions
5. Final result displayed and logged

## 🧰 Tech Stack

| Category              | Tools/Technologies                        |
|-----------------------|-------------------------------------------|
| Programming Language  | Python 3.10+                              |
| ML Libraries          | Scikit-learn, XGBoost, CatBoost           |
| Image Processing      | OpenCV, PIL                               |
| Frontend Interface    | Streamlit                                 |
| Data Handling         | Pandas, NumPy                             |
| Visualization         | Matplotlib, Seaborn                       |
| Database              | SQLite3                                   |
| IDEs                  | Jupyter Notebook, VS Code, PyCharm        |

## 🗃 Dataset

- ECG image dataset sourced from the [Mendeley Data Repository](https://data.mendeley.com/)
- Labels: Normal, Abnormal, Myocardial Infarction (MI), History of MI

## 📈 Model Performance

| Model         | Accuracy |
|---------------|----------|
| Random Forest | 89%      |
| XGBoost       | 89%      |
| CatBoost      | 90%      |
| *Soft Voting Classifier* | *91%* |

- Evaluation metrics used: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## 🧪 How to Run

1. *Install dependencies:*
   ```bash
   pip install -r requirements.txt
