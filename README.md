# Loan-Approval-Prediction
Machine Learning project for predicting loan approval using Python, synthetic applicant data, exploratory data analysis, and classification algorithms.
# Loan Approval Prediction System Using Machine Learning

A machine learning project that predicts loan approval outcomes using applicant demographics, financial information, and employment details. Developed using Python and Scikit-learn as part of the Infobharat Interns Machine Learning Internship Program.

## Project Overview

The Loan Approval Prediction System demonstrates an end-to-end supervised machine learning workflow. It uses a synthetic dataset to explore applicant characteristics, preprocess data, train classification models, evaluate their performance, and predict loan approval outcomes.

**Project Type:** Supervised Machine Learning — Binary Classification  
**Language:** Python  
**Dataset Size:** 2,000 synthetic applicant records  
**Target Variable:** `LoanApproved` (0 = Rejected, 1 = Approved)

## Objectives

- Generate a synthetic loan applicant dataset.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA).
- Visualize relationships between financial attributes and loan approval.
- Train and compare multiple classification algorithms.
- Evaluate model performance using classification metrics.
- Develop an interactive loan prediction system.

## Features

- Synthetic dataset generation using NumPy and Pandas.
- Missing-value handling and duplicate removal.
- Categorical encoding and numerical feature scaling.
- Exploratory data analysis and visualization.
- Comparison of Logistic Regression, Decision Tree, and Random Forest.
- Model evaluation using accuracy, precision, recall, F1-score, and a confusion matrix.
- Interactive console-based prediction with input validation.
- Model serialization using Joblib.

## Dataset Description

The dataset contains the following features:

| Feature | Description |
|---|---|
| ApplicantID | Unique applicant identifier |
| Gender | Applicant gender |
| Age | Applicant age in years |
| MonthlyIncome | Monthly income in INR |
| LoanAmount | Requested loan amount in INR |
| CreditScore | Applicant credit score |
| EmploymentStatus | Employment category |
| ExistingLoans | Number of existing loans |
| LoanTerm | Loan duration in months |
| PropertyArea | Urban, Semi-Urban, or Rural |
| LoanApproved | Target: 0 = Rejected, 1 = Approved |

The dataset is synthetically generated for educational purposes. Approval labels are based on an illustrative probability formula rather than real lending records.

## Technologies Used

- **Python** — Programming language
- **NumPy** — Numerical computations and synthetic data generation
- **Pandas** — Data manipulation and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Scikit-learn** — Preprocessing, classification, and model evaluation
- **Joblib** — Model serialization
- **Google Colab / Jupyter Notebook** — Development environment
- **GitHub** — Version control and project hosting

## Project Workflow

1. **Dataset Generation:** Generate 2,000 synthetic applicant records.
2. **Data Inspection:** Examine dataset dimensions, data types, missing values, and duplicates.
3. **Data Preprocessing:** Impute missing values, encode categorical features, and scale numerical features.
4. **Exploratory Data Analysis:** Investigate applicant characteristics and approval patterns.
5. **Data Visualization:** Generate charts to communicate findings.
6. **Model Training:** Train Logistic Regression, Decision Tree, and Random Forest classifiers.
7. **Model Evaluation:** Compare classification performance on a held-out test dataset.
8. **Interactive Prediction:** Accept applicant details and predict the model's output.
9. **Model Saving:** Serialize the selected model pipeline for reuse.

## Data Visualizations

The project includes the following visualizations:

- Loan approval outcome distribution.
- Loan approval by employment status.
- Correlation heatmap of numerical features.
- Monthly income versus requested loan amount.
- Confusion matrix for the selected classification model.

## Machine Learning Models

### 1. Logistic Regression
A baseline classification algorithm for predicting binary outcomes.

### 2. Decision Tree Classifier
A tree-based algorithm that learns decision rules from input features.

### 3. Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees.

The models are compared using accuracy, precision, recall, and F1-score. The selected model is determined using the evaluation results generated during the experiment.

## Model Evaluation

The following metrics are used to evaluate the models:

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall classification correctness |
| Precision | Measures the correctness of positive predictions |
| Recall | Measures how many actual positive cases are identified |
| F1-score | Balances precision and recall |
| Confusion Matrix | Summarizes correct and incorrect predictions |

**Results:** Insert the actual evaluation results from your completed notebook here. No performance values are assumed in advance.

## Project Structure

```text
Loan-Approval-Prediction/
│
├── Loan_Approval_Prediction.ipynb
├── loan_approval.py
├── loan_approval_dataset.csv
├── loan_approval_model.pkl
├── README.md
├── .gitignore
│
└── visualizations/
    ├── approval_distribution.png
    ├── employment_approval.png
    ├── correlation_heatmap.png
    ├── income_vs_loan_amount.png
    └── confusion_matrix.png
```

Include only files that you have actually created. The visualization images can be added after saving the charts from your notebook.

## Installation and Setup

### Prerequisites

- Python 3.10 or a compatible Python version
- pip
- Jupyter Notebook or Google Colab
- Git (optional for command-line uploads)

### Step 1: Clone the Repository

```bash
git clone https://github.com/Manugoud903/Loan-Approval-Prediction.git
cd Loan-Approval-Prediction
```

### Step 2: Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter
```

### Step 3: Run the Notebook

```bash
jupyter notebook Loan_Approval_Prediction.ipynb
```

Alternatively, upload the notebook to Google Colab and execute the cells in order.

### Step 4: Run the Python Application

If the standalone Python script has been prepared with the prediction interface:

```bash
python loan_approval.py
```

Ensure that the required model and dataset files are available and that the script loads the trained pipeline correctly.

## Key Learnings

- Understanding the end-to-end machine learning lifecycle.
- Generating and validating structured datasets.
- Handling missing values and categorical variables.
- Performing exploratory data analysis.
- Training and comparing classification algorithms.
- Evaluating model performance using multiple metrics.
- Building input validation into a prediction interface.
- Organizing and documenting a machine learning project for GitHub.

## Limitations and Ethical Considerations

- The dataset is synthetic and does not represent actual loan applicants.
- Approval labels are generated from an illustrative formula.
- Results on synthetic data do not demonstrate real-world lending accuracy.
- Gender and other sensitive attributes require careful fairness assessment before any real-world application.
- This project is for learning and demonstration purposes only, not for making financial or lending decisions.

## Future Enhancements

- Develop a web interface using Streamlit.
- Add feature importance analysis and model explainability.
- Create downloadable prediction reports.
- Perform more comprehensive validation and fairness analysis.
- Deploy an educational demonstration online.

## Author

**D.Manogna Goud.**

B.Tech — Computer Science and Engineering (Artificial Intelligence and Machine Learning)

Machine Learning Internship Project — Infobharat Interns

GitHub: [Manugoud903](https://github.com/Manugoud903)

---

If you find this project useful, feel free to explore the repository and learn from the implementation.

**Disclaimer:** This project is intended exclusively for educational purposes..
