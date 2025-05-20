# ❤️ Heart Disease Prediction Using Machine Learning

This project uses a machine learning model to predict whether a person has heart disease based on medical attributes such as chest pain type, cholesterol, maximum heart rate, and more.

## 🧠 Algorithms Used

- Random Forest Classifier
- Decision Tree Classifier

## 📁 Dataset

The dataset is based on the **UCI Heart Disease Dataset**, which contains the following features:

- `age`: Age of the patient
- `sex`: Sex (1 = male, 0 = female)
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the ST segment
- `ca`: Number of major vessels (0–3) colored by fluoroscopy
- `thal`: 3 = normal; 6 = fixed defect; 7 = reversible defect
- `target`: 0 = no disease, 1 = disease

## 🛠️ Features Selected

Based on correlation analysis, the following features were chosen:
- `cp`
- `thalach`
- `exang`
- `oldpeak`

## 📊 Visualizations

- Correlation heatmap of features
- Confusion matrix for model performance
- Bar chart of feature importances (Random Forest)

## ⚙️ Model Evaluation

Metrics used to evaluate performance:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

## 📦 Requirements

- Python 3.x
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

Install using:
```bash
pip install pandas scikit-learn matplotlib seaborn
