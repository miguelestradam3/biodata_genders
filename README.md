# ⚖️ Gender Classification using Height and Weight

This project demonstrates how to build a machine learning model that predicts a person's **gender** based on their **height** and **weight** measurements. The notebook follows a complete machine learning workflow, including exploratory data analysis (EDA), data preprocessing, feature scaling, handling class imbalance with **SMOTE**, and training a **Logistic Regression** classifier.

This project is designed as a beginner-friendly introduction to binary classification using Scikit-learn.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Correlation analysis
- Data visualization with Seaborn
- Label encoding for categorical data
- Feature scaling using `StandardScaler`
- Train/Test split
- Class imbalance handling with `SMOTE`
- Logistic Regression classifier
- Model evaluation using multiple metrics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn `(SMOTE)`
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
```

---

## 📊 Dataset

The project uses a **Height and Weight** dataset containing physical measurements for individuals.

### Features

| Feature | Description |
|----------|-------------|
| Height | Height of the individual |
| Weight | Weight of the individual |
| Gender | Target variable (Male or Female) |

The target variable is converted into numerical values using **LabelEncoder** before training the model.

---

## 🔍 Exploratory Data Analysis

The notebook includes several exploratory analysis steps, such as:

- Dataset inspection
- Summary statistics
- Correlation analysis
- Scatter plots
- Distribution visualization
- Feature relationship analysis

These visualizations help identify patterns between height, weight, and gender.

---

## ⚙️ Machine Learning Workflow

The notebook performs the following steps:

- Load the dataset
- Explore and visualize the data
- Encode categorical labels
- Split the dataset into training and testing sets
- Balance the training data using **SMOTE**
- Standardize numerical features using `StandardScaler`
- Train a **Logistic Regression** model
- Generate predictions
- Evaluate model performance

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

These metrics provide an overview of the classifier's predictive performance.

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
main.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Perform exploratory data analysis
- Encode categorical variables
- Handle imbalanced datasets using SMOTE
- Standardize numerical features
- Train a Logistic Regression classifier
- Evaluate binary classification models using standard metrics

---

## 🔮 Future Improvements

- Compare additional classification models (Random Forest, SVM, XGBoost)
- Perform hyperparameter tuning
- Apply cross-validation
- Visualize decision boundaries
- Deploy the model as a Streamlit web application
