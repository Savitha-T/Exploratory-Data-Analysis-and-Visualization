# Exploratory-Data-Analysis-and-Visualization
# Breast Cancer EDA and Visualization with Deep Learning

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA), data visualization, and deep learning for classifying breast cancer tumors as **Benign** or **Malignant** using the Breast Cancer Wisconsin (Diagnostic) dataset.

The project analyzes tumor-related numerical features, identifies patterns and relationships, and builds a Multilayer Perceptron (MLP) classifier to evaluate classification performance.

## 🎯 Objectives

- Understand and explore the breast cancer dataset.
- Identify missing values, duplicates, outliers, and feature relationships.
- Perform data cleaning, preprocessing, and feature scaling.
- Create visualizations to understand data distributions and patterns.
- Build and evaluate a deep learning classification model.
- Analyze model performance using appropriate evaluation metrics.

## 📊 Dataset Description

- **Dataset:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Original records:** 569
- **Numerical features:** 30 after removing unnecessary columns
- **Target variable:** Diagnosis
- **Classes:** Benign (B) and Malignant (M)

The dataset contains numerical measurements derived from digitized images of fine needle aspirates of breast masses.

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow / Keras

## 🔍 Exploratory Data Analysis

The project includes:

- Dataset structure and summary statistics
- Missing-value and duplicate analysis
- Outlier analysis using boxplots and the IQR method
- Diagnosis class distribution
- Feature distribution histograms
- Correlation heatmap
- Feature relationship scatterplots
- Comparison of feature values between diagnosis classes

## ⚙️ Data Preprocessing

The following preprocessing steps are performed in the notebook:

1. Remove unnecessary identifier and empty columns.
2. Check for missing values and duplicate records.
3. Encode the diagnosis labels.
4. Split the data into training, validation, and testing sets.
5. Impute missing values if required.
6. Standardize numerical features using training data statistics.

## 🧠 Deep Learning Model

A Multilayer Perceptron (MLP) neural network is used for binary classification.

The model is trained to predict whether a tumor is benign or malignant. Hyperparameter configurations are compared using validation performance, and the selected model is evaluated on the test dataset.

## 📈 Model Evaluation

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC curve and AUC
- Training and validation accuracy/loss curves

**Note:** Refer to the executed notebook for the verified final evaluation metrics.


Replace the example filenames with the actual filenames uploaded to this repository.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Download the dataset from the Kaggle link above.
4. Upload the CSV file when prompted, or update the dataset path in the notebook.
5. Install any missing dependencies if required.
6. Run the notebook cells in order.
7. Review the generated visualizations and evaluation results.

## 📌 Results

The project evaluates how well an MLP model classifies benign and malignant tumors based on numerical features.

The final performance metrics and visualizations should be taken from the executed notebook and included in the project report.
## 🔮 Future Scope

- Evaluate additional machine learning and deep learning models.
- Perform more systematic hyperparameter tuning.
- Validate performance on independent datasets.
- Improve model interpretability using feature-importance and explainability techniques.
- Explore deployment as an educational demonstration application.

## ⚠️ Disclaimer

This project is intended for educational and academic purposes only. It is not a medical diagnostic tool and must not be used as a substitute for professional medical advice.

## 📚 References

1. Kaggle, *Breast Cancer Wisconsin (Diagnostic) Dataset*: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
2. Pandas documentation: https://pandas.pydata.org/docs/
3. Scikit-learn documentation: https://scikit-learn.org/stable/
4. TensorFlow documentation: https://www.tensorflow.org/guide

---

**Project Type:** Exploratory Data Analysis, Data Visualization, and Deep Learning Classification  
**Language:** Python  
**Environment:** Google Colab / Jupyter Notebook
