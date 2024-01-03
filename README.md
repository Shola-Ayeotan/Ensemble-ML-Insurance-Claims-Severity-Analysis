
# All-State Insurance Claims Severity Prediction with Ensemble Learning

## Overview
This project focuses on predicting the severity and cost of insurance claims for All-State, a leading personal insurance company in the US. By leveraging ensemble machine learning algorithms, we analyze and predict the impact of unforeseen events on insurance claims. The project encompasses everything from data cleaning to model deployment.

## Tech Stack
- **Language:** Python
- **Key Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, Flask (for API)
- **Ensemble Models:** Random Forest Regressor, Gradient Boosting Regressor

## Getting Started

### Prerequisites
- Python 3.x
- Dependencies listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```
   git clone [repository URL]
   ```
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
- Execute the Jupyter notebook `Insurance_Claims_Severity_Prediction.ipynb` for a comprehensive walkthrough of the data analysis, preprocessing, and model training.
- Deploy the model using the Flask API in `insurance_claim_model_api.py`.

## Model Overview
The project includes several critical stages:
1. **Dataset Overview:** Initial assessment of dataset structure and content.
2. **Exploratory Data Analysis (EDA):** In-depth analysis for a deeper understanding of the data.
3. **Data Cleaning and Preprocessing:** Addressing missing values, encoding categorical variables, etc.
4. **Outlier Treatment:** Identifying and managing outliers in the dataset.
5. **Feature Selection:** Using techniques to choose relevant features.
6. **Ensemble Machine Learning Models:** Implementing advanced ensemble methods for robust model development.
7. **Hyperparameter Tuning:** Fine-tuning the models for optimal performance.
8. **Model Validation:** Evaluating the model's effectiveness.
9. **Deployment:** Employing a Flask API for model deployment.

## Results
The models were evaluated using Root Mean Squared Error (RMSE) and R-squared metrics. These metrics provided insights into the model's accuracy and the proportion of variance in the dependent variable that's predictable from the independent variables. Detailed analysis and results are presented in the notebook.

## Contributing
Contributions to this project are welcome. Please follow these guidelines:
- Fork the repository and create your branch from `main`.
- Ensure to update tests as appropriate.
- Submit a pull request with a detailed description of your changes.


