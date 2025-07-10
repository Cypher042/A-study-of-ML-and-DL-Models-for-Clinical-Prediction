# Heart Disease Prediction

This project focuses on predicting the presence of heart disease in patients using various clinical parameters. It leverages multiple machine learning and deep learning models and evaluates their performance using standard metrics such as **Accuracy**, **Precision**, **Recall**, and **AUC-ROC**.



---

## 📊 Dataset

The dataset is sourced from Kaggle’s repository. It contains **303 patient records** with **13 features** and **1 target variable** indicating the presence of heart disease.

### Features

| Feature     | Description |
|-------------|-------------|
| `age`       | Age in years |
| `sex`       | Sex (1 = male, 0 = female) |
| `cp`        | Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic) |
| `trestbps`  | Resting blood pressure (in mm Hg) |
| `chol`      | Serum cholesterol in mg/dl |
| `fbs`       | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg`   | Resting ECG results (0 = normal, 1 = ST-T wave abnormality, 2 = probable or definite left ventricular hypertrophy) |
| `thalach`   | Maximum heart rate achieved |
| `exang`     | Exercise-induced angina (1 = yes, 0 = no) |
| `oldpeak`   | ST depression induced by exercise relative to rest |
| `slope`     | Slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping) |
| `ca`        | Number of major vessels (0–3) colored by fluoroscopy |
| `thal`      | Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect) |

### Target

- `num`: Presence of heart disease (0 = no disease, 1 = disease present)

---

## 📦 Dependencies

Ensure the following Python libraries are installed (best used with Python 3.11.0):

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow` / `keras`
- `plot_keras_history`

---

## 🧠 Models Used

This project explores both traditional machine learning and modern deep learning models to compare predictive performance:

### Machine Learning Models:
- ✅ Logistic Regression  
- 🌲 Decision Tree  
- 🌳 Random Forest  
- ➖ Support Vector Machine (SVM)

### Deep Learning Models:
- 🔷 Feedforward Neural Network (FNN)
- 🧠 Artificial Neural Network (ANN)
- 🔁 Gated Recurrent Unit (GRU)
- ⏳ Long Short-Term Memory (LSTM)

Each model is trained and evaluated on the same dataset to ensure a fair comparison.

---

## 📈 Evaluation Metrics

Each model is evaluated using the following performance metrics:

- **Accuracy** – Overall correctness of the model
- **Precision** – Correctness of positive predictions
- **Recall** – Model’s ability to detect positives
- **AUC-ROC** – Area under the ROC curve to evaluate classifier performance


