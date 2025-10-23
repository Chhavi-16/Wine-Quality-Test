
# 🍷 Wine Quality Test

This project analyzes the **Wine Quality dataset** and builds a machine learning model to predict wine quality based on its chemical characteristics.

---

## 📘 Project Overview

The notebook performs:
- Data loading and cleaning  
- Exploratory Data Analysis (EDA) using plots and correlations  
- Feature selection and preprocessing  
- Model training using **Random Forest Classifier**  
- Evaluation of model performance (accuracy metrics)

---

## 🧠 Technologies Used

- Python 3.x  
- NumPy  
- pandas  
- Matplotlib  
- Seaborn  
- scikit-learn  

---

## 📊 Dataset

**Dataset used:** `WineQT.csv`  
The dataset contains physicochemical properties (inputs) and quality scores (outputs) for different wine samples.

| Feature | Description |
|----------|-------------|
| fixed acidity | Amount of tartaric acid in wine |
| volatile acidity | Amount of acetic acid |
| citric acid | Natural acid in wine |
| residual sugar | Sugar left after fermentation |
| chlorides | Salt content |
| free sulfur dioxide | SO₂ not bound to other molecules |
| total sulfur dioxide | Sum of free and bound forms |
| density | Density of the wine |
| pH | Acidity level |
| sulphates | Sulfur dioxide indicator |
| alcohol | Alcohol percentage |
| quality | Target variable (score 0–10) |

Dataset Source: [UCI Machine Learning Repository - Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/Wine-Quality-Test.git
   cd Wine-Quality-Test
   ```

2. **Install required libraries**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook
   ```
   Then open `1cff1e7f-eb7d-4704-8617-75a7b9d990ed.ipynb`.

4. **Run all cells** to reproduce the results.

---

## 📈 Model Used

The notebook uses a **Random Forest Classifier** from `scikit-learn` to predict wine quality.  
Model evaluation is done using accuracy metrics to determine performance.

---

## 💡 Results

- Random Forest achieved a good prediction accuracy for wine quality.
- Feature correlation showed **alcohol**, **sulphates**, and **volatile acidity** as key contributors to quality.

---


## 👩‍💻 Author

**Vaishnavi Kumari**  
📧 https://github.com/Chhavi-16


