# 🩺 Diabetes Prediction using Machine Learning

This project aims to predict the onset of diabetes using machine learning models trained on the PIMA Indian Diabetes dataset. It demonstrates a complete data science workflow — from preprocessing and feature engineering to model evaluation and visualization.

## 📁 Project Structure

```
diabetes-prediction/
│
├── diabetes.csv                    # Dataset (PIMA Indian dataset)
├── diabetes_prediction.ipynb      # Jupyter Notebook with full code and analysis
├── README.md                      # Project overview
└── requirements.txt               # (Optional) Python dependencies
```

## 📊 Dataset

- **Source**: PIMA Indian Diabetes dataset
- **Rows**: 768
- **Features**: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target**: `Outcome` (0 = No Diabetes, 1 = Diabetes)

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn (Logistic Regression, Random Forest, SVM, etc.)

## 📈 Model Performance

- Best model: **Random Forest**
- Accuracy: **89%**
- AUC Score: **0.87**
- Evaluation methods: 5-Fold Cross-Validation, Confusion Matrix, ROC Curve

## 📌 Key Features

- Data cleaning and imputation (handling zero values)
- Feature scaling and normalization
- Model training and tuning
- Performance visualization (ROC, confusion matrix)
- Comparative analysis of multiple algorithms

## 🚀 How to Run

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```
   jupyter notebook diabetes_prediction.ipynb
   ```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## 🤝 Acknowledgements

- Dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes)
