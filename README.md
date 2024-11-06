
# Customer Churn Prediction in E-Commerce

## Project Description
This project aims to predict customer churn within an e-commerce company by analyzing customer behavior and demographic data. By identifying key drivers of churn and developing predictive models, the project assists in strategizing retention efforts to improve customer loyalty and business revenue.

## Objectives
- **Identify key factors contributing to customer churn.**
- **Build a machine learning model for predicting customer churn.**
- **Provide actionable insights to inform customer retention strategies.**

## Project Structure
This project is organized into several key sections, each representing a critical phase in the analysis process:

1. **Business Understanding**: Establishing the context and defining the business objectives for customer churn analysis.
2. **Preliminary Data Understanding**: Initial exploration of the data, identifying key attributes and potential challenges.
3. **Exploratory Data Analysis (EDA)**: Detailed analysis to uncover patterns, trends, and correlations in the data, especially those related to churn.
4. **Data Cleaning**: Handling missing values, correcting data inconsistencies, and preparing the dataset for modeling.
5. **Feature Engineering**: Creating and refining features that enhance model performance.
6. **Rule-Based Model**: Implementing a baseline rule-based model to set initial benchmarks for churn prediction.
7. **Scaling and Encoding Data**: Applying transformations to standardize data and encode categorical features for model compatibility.
8. **Modeling & Evaluation**: Building, evaluating, and comparing machine learning models to select the best predictor of churn.

## Dataset
- **Source**: [E-Commerce Customer Churn Dataset](#) *(link if available)*
- **Description**: The dataset includes features such as customer tenure, satisfaction scores, complaint history, number of addresses, and more.

## Feature Importance & Model Interpretability
- **Top Features**: Based on feature importance analysis and SHAP values, key predictors of churn include tenure, satisfaction score, complaint history, and city tier.
- **Interpretation**: The analysis provides insights into the impact of each feature on churn, helping to target specific factors in customer retention strategies.

## Model Evaluation Metric
- **F2 Score**: The F2 score is prioritized to balance recall, focusing on identifying potential churners while controlling for false positives. This ensures effective targeting of high-risk customers without excessive costs.

## Strategic Recommendations
1. **Engagement for Low Tenure Customers**: Offer onboarding support and retention incentives for new customers.
2. **Enhance Satisfaction Monitoring**: Regularly collect and act on customer satisfaction feedback.
3. **Address Management Improvements**: Simplify address-related processes to accommodate customers with multiple addresses.
4. **Effective Complaint Resolution**: Improve complaint handling to retain at-risk customers.
5. **City-Specific Marketing**: Tailor promotional strategies to align with regional preferences.

## Installation and Requirements
Install the required libraries with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook and execute the steps outlined above to run the analysis.

## Results and Insights
- **Model Performance**: The chosen model achieved a high F2 score, ensuring effective recall of churned customers.
- **Key Findings**: The top factors influencing churn have been identified, providing clear guidance on areas for improvement.

## Future Work
Potential next steps include fine-tuning hyperparameters, gathering additional data, and enhancing cross-validation techniques for better generalizability.

## Contributors
- **Data Analyst Team**: Responsible for data analysis and model development.

## License
Specify the license, e.g., MIT License.
