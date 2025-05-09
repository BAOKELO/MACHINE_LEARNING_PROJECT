# CUSTOMER RETENTION: Telecom Churn Reduction using Predictive Analytics



### Project Overview
Customer churn is a significant issue in the telecom industry, affecting revenue and long-term growth. This project uses machine learning models to predict whether a customer is likely to churn based on their usage behavior and service patterns.
The goal is to enable businesses to proactively retain customers by identifying those at risk and implementing targeted retention strategies.

### Business Problem
Customer churn is when a customer stops using a service or product. It is a common and costly problem for telecom companies. It directly affects companies' revenue.
Key Questions:
* Which usage trends and service interactions accurately signal churn?
* Which models can we use to help accurately identify customers likely to churn?
* What retention strategies should be prioritized based on different customer risk profiles?

### Data Understanding 
The Data was sourced from Kaggle - Churn in Telecoms Dataset
we loaded the data, Identified our variables,encoded categorical variables, nomalized numerical features
Checked on churn distributions and class imbalances
Visualized features with the most correlation

### Modelling
* Logistic Regression: Used as a baseline for its simplicity and interpretability

* Decision Tree: Used for capturing complex, non-linear relationships in the data

* Evaluated models using Accuracy, Precision, Recall, F1 Score, and ROC-AUC

* Decision Tree showed superior performance in identifying churners

  created confusion matrix to better understand each model and find the True positives and negatives

Modelling helps in:
* early identification of high-risk customers
* strategic decision-making based on data-driven insights
* implementing retention efforts to the correct group
* Reduceing churn-related revenue loss

### COMPARATIVE ANALYSIS AND BUSINESS IMPLICATIONS
Did comparative analysis and connected model results to business impact

Proposed actionable retention strategies based on model outputs

| Metric    | Logistic Regression | Decision Tree |
| --------- | ------------------- | ------------- |
| Accuracy  | 0.78                | 0.93          |
| Precision | 0.39                | 0.76          |
| Recall    | 0.77                | 0.76          |
| F1 Score  | 0.52                | 0.76          |
| ROC-AUC   | 0.835               | 0.86          |

Decision Tree is the preferred model since it performed very well compared to the Logistic Regression

### RECOMMENDATIONS

* Segment Customers: Use Decision Trees to group churn-prone users and target them with tailored offers.

* Improve Support: Train service teams to resolve issues better and upsell when possible.

* Time-Based Offers: Create plans for peak and off-peak usage, like midnight bundles or hourly rates.

* Loyalty Programs: Offer rewards like bonus airtime, points, and low-interest credit to boost loyalty.




