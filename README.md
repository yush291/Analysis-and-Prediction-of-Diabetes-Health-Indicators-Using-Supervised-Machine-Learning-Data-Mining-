# Diabetes Risk Prediction Using Machine Learning

## Project Overview
This project focuses on analyzing and predicting diabetes risk using supervised machine learning models. The dataset used contains various health indicators and demographic features that are processed and analyzed to build predictive models capable of classifying individuals into three categories: No Diabetes, Prediabetes, or Diabetes.

---

## Objectives
- Develop a machine learning model to predict diabetes risk.
- Preprocess and analyze health-related data for reliable predictions.
- Evaluate model performance using metrics like accuracy, F1-score, and ROC-AUC.

---

## Dataset
**Name:** Diabetes Health Indicators Dataset  
**Source:** [Kaggle](https://www.kaggle.com/)  
**Number of Instances:** 253,680  
**Number of Features:** 22 

### Key Features:
- **Target Variable:** `Diabetes_012` (0 = No Diabetes, 1 = Prediabetes, 2 = Diabetes)
- Health indicators such as `BMI`, `HighBP`, `HighChol`, and `PhysActivity`
- Lifestyle variables like `Smoker`, `Fruits`, `Veggies`, and `HvyAlcoholConsump`
- Demographic variables including `Age`, `Education`, and `Income`

---

## Methodology
### 1. **Data Preprocessing**
- Handle missing values (imputation or removal).
- Scale continuous features and encode categorical variables.
- Split data into training (60%), validation (20%), and testing (20%) sets.

### 2. **Exploratory Data Analysis (EDA)**
- Visualize feature distributions using histograms and box plots.
- Analyze feature correlations and detect outliers.

### 3. **Model Selection and Training**
- Evaluate machine learning models: Logistic Regression, Decision Trees, Random Forest, and SVM.
- Use cross-validation to avoid overfitting and ensure generalization.

### 4. **Hyperparameter Tuning**
- Apply grid search and random search techniques to optimize model parameters.

### 5. **Model Evaluation**
- Evaluate models using metrics like:
  - **Accuracy**
  - **Precision and Recall**
  - **F1-Score**
  - **ROC-AUC Curve**

---

## Results
- Models are compared based on their performance metrics.
- The best-performing model is selected for deployment.

---


## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-risk-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook DataMining_Lab04.ipynb
   ```

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas, NumPy for data manipulation
  - Matplotlib, Seaborn for visualization
  - Scikit-learn for machine learning models

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- [Kaggle](https://www.kaggle.com/) for providing the dataset.
