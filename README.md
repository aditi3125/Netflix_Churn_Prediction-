# Netflix Customer Churn Prediction

The goal of this project is to predict customer churn—whether a Netflix user is likely to leave or stay—using Machine Learning.
Accurate churn prediction enables streaming platforms to reduce customer attrition, improve user engagement, and optimize retention strategies.

##  About the Project

Customer churn is a major challenge for subscription-based businesses.
This project implements a Random Forest–based Machine Learning model wrapped inside a Scikit-learn Pipeline to ensure consistent preprocessing and reliable predictions.

#### The system is capable of:

1. Automatically preprocessing customer data
2. Predicting churn for existing and new customers
3. Presenting results using clear visualizations (pie charts & confusion matrix)
   
## Dataset Overview
Total Customers: 5,000

Target Variable:

churned = 0 → Not Churned

churned = 1 → Churned

### Features Include:

1. Age
2. Gender
3. Region
4. Device Type
5. Subscription Type
6. Payment Method
7. Watch Hours
8.Monthly Fee
9.Average Watch Time per Day
10.Number of Profiles
11.Last Login Activity

Note: The full dataset is private. A sample dataset (10–20 rows) is included in the repository for demonstration and testing purposes.

## Model & Approach
   1. Handled missing values using median for numerical features and most frequent value for categorical features
   2. Applied feature scaling to numerical data
   3. Used one-hot encoding for categorical variables
   4. Implemented a Random Forest Classifier with 100 trees
   5. Combined preprocessing and model into a single Scikit-learn Pipeline
   6. Ensured consistent preprocessing, prevented data leakage, and enabled deployment readiness
   7. No data leakage

## Model Performance & Results

1. Accuracy Rate: 97.8%
2. Confusion Matrix Summary
   1. True Negatives (Not Churn correctly predicted): 490
   2. True Positives (Churn correctly predicted): 488
   3. False Positives: 8
   4. False Negatives: 14
   5. This indicates very few misclassifications, showing strong model reliability.

📊 Visual Insights

#### Pie Charts:
  1. Display churn vs non-churn probability for individual customers

#### Confusion Matrix Heatmap:
  1. Shows strong classification accuracy with minimal errors
  2. These visuals make predictions easy to interpret for non-technical stakeholders.

  <img width="716" height="660" alt="image" src="https://github.com/user-attachments/assets/3920eda0-969d-4343-a57a-7cf52db3eb3c" />
  <img width="505" height="371" alt="image" src="https://github.com/user-attachments/assets/7e55ca50-4b4b-46dc-a338-0539be5fa54b" />
  <img width="536" height="377" alt="image" src="https://github.com/user-attachments/assets/849c56c6-cb76-43a8-92a3-5147d5d5d375" />
  
## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-churn-prediction.git
```

2. Navigate to the project directory
```bash
cd netflix-churn-prediction
```

3. Install the required dependencies
```bash
pip install -r requirements.txt
```

4. Run the churn prediction model
```bash
python churn_prediction.py
```
## Key Takeaways

  1. Built a high-accuracy churn prediction system (97.8%)
  2. Applied end-to-end ML pipeline design
  3. Handled real-world mixed data (numerical + categorical)
  4. Generated interpretable probability-based predictions
  5. Demonstrated a business-focused ML use case

## Conclusion

This project demonstrates a real-world Machine Learning application for customer churn prediction in the streaming industry.
It highlights strong skills in data preprocessing, pipeline-based modeling, evaluation, and visualization, making it highly suitable for Data Science and Machine Learning roles.
   
