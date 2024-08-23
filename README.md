# german_bank_loan
# Bank Customer Default Prediction

The objective of this project is to forecast the default status of bank clients by considering multiple factors, including job duration, savings balance, percentage of income, and other relevant variables. The dataset utilized in this study comprises historical data pertaining to 1000 consumers, encompassing 17 distinct parameters, one of which is the objective variable "default."

## Project Structure

### 1. Introduction
- **Context**: Understanding the risk of customer default is crucial for banks in managing credit risk and making informed lending decisions.
- **Objective**: To explore the dataset, build predictive models, and identify key features that influence the likelihood of default.
- **Research Questions**:
  - Which features are most predictive of customer default?
  - How do different machine learning models perform in predicting default status?
  - What are the patterns or correlations in the data that could inform better credit decisions?

### 2. Methods and Materials
- **Data Source**: The dataset used for this project is provided as `German_bank.csv`.
- **Exploratory Data Analysis (EDA)**:
  - Data overview and summary statistics
  - Visualization of feature distributions and relationships
  - Correlation analysis
- **Data Preparation**:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling
- **Modeling**:
  - Models considered: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Support Vector Machine (SVM)
  - Evaluation Metrics: Accuracy, Precision, Recall, ROC-AUC score

### 3. Results
- **Model Performance**: 
  - Detailed performance metrics for each model.
  - Visualizations including confusion matrices, ROC curves, and feature importance plots.
- **Key Findings**:
  - Identification of the most influential features in predicting default.
  - Comparative analysis of model performances.

### 4. Discussion
- **Interpretation of Results**: 
  - Insights derived from model results.
  - Practical implications for credit risk management.
- **Limitations**:
  - Potential biases or limitations in the dataset and methodology.
  - Suggestions for future work to improve model accuracy and generalizability.

### 5. Conclusion
- **Summary**: 
  - Recap of the main findings and their significance.
  - Final thoughts on the utility of the models in real-world banking scenarios.

## Installation and Usage

### Prerequisites
- Python 3.x
- Required Python packages (can be installed via `requirements.txt`)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/esaiudya87/german_bank_loan.git
