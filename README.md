#  Netflix Churn Prediction  

The aim is to **predict customer churn** (whether a Netflix user will leave or stay) using **Machine Learning**.  
A well-trained model helps streaming platforms like Netflix reduce customer loss and improve engagement.

## About the Project
Customer churn is one of the biggest challenges for subscription-based businesses.  
This project builds a **Random Forest-based Machine Learning Model** wrapped in a **Scikit-learn Pipeline** to:
- Preprocess customer data automatically  
- Predict churn for existing or new customers  
- Provide results in **visual formats** ( charts)  
## Dataset
- Total Customers: **5000**  
- Features: Age, Gender, Region, Device, Subscription Type, Payment Method, Watch Hours, Monthly Fee, etc.  
- Target Variable: `churned` (0 = Not Churn, 1 = Churn)  

Note: The full dataset is private. Only a **sample dataset (10–20 rows)** is included for testing.


##  Model & Approach
- **Preprocessing:**  
  - Handle missing values (median / most frequent)  
  - Scale numeric features  
  - One-hot encode categorical features  

- **Algorithm Used:**  
  - Random Forest Classifier (n_estimators=100)  

- **Pipeline Advantage:**  
  New customer data passes through the same preprocessing steps automatically before prediction.

---
##Results
Model Accuracy: 97.8%
Confusion Matrix: Shows very few false positives & negatives.
Visual Outputs:
Pie chart of churn vs not churn predictions
