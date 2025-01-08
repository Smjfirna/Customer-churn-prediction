# Customer Churn Prediction Project

## Project Description
This project aims to predict customer churn in the telecommunications industry using machine learning techniques. By analyzing customer data, the model predicts whether a customer is likely to churn, helping businesses identify high-risk customers and take action to retain them. A dashboard is also created to visualize the churn prediction results and the factors influencing customer churn.

## Data Set
The dataset used in this project comes from a telecom company and contains customer information such as demographic data, account information, service usage, and customer churn status. The dataset includes features such as customer age, contract type, monthly charges, and whether a customer has churned (1) or not (0). The dataset was pre-processed to handle missing values, normalize numerical features, and encode categorical variables.

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**:  
   - Visualize and understand data distributions and relationships using histograms, box plots, and heatmaps.  
   - Identify key factors that may influence customer churn.

2. **Data Preprocessing**:  
   - Handle missing values and categorical variables.  
   - Scale numerical features and split data into training and test sets.

3. **Model Building**:  
   - Train machine learning models (e.g., Logistic Regression, Decision Trees) to predict customer churn.  
   - Evaluate models using metrics such as accuracy, precision, recall, and F1-score.

4. **Dashboard Creation**:  
   - Build an interactive dashboard using Power BI to display key metrics and churn predictions.  
   - Allow users to filter data and explore customer churn insights interactively.

5. **Model Evaluation and Discussion**:  
   - Analyze model performance and identify areas for improvement.  
   - Provide business recommendations based on churn insights.

## Tools and Library
- **Python Libraries**: 
  - Pandas, NumPy, Scikit-learn for data manipulation, model building, and evaluation.
  - Matplotlib and Seaborn for data visualization.
- **Power BI**: For building the interactive dashboard.
- **Collaboratory**: To document the analysis, model development, and results.

## Result and Discussion
The model successfully predicted customer churn with an **accuracy of X%** (replace with actual result). Key factors contributing to churn include contract type, monthly charges, and service usage. The dashboard provides valuable insights for business decision-makers to focus on high-risk customers and design retention strategies.

**Business Implications**:  
- Customers with **monthly contracts** tend to have a higher churn rate than those with annual contracts.
- **High monthly charges** are correlated with higher churn.  
- The interactive dashboard enables stakeholders to view the churn rate and predict customer behavior easily.

## Clone Repository
To clone this repository, run the following command in your terminal:
```
git clone https://github.com/Smjfirna/Customer-churn-prediction.git
```
