# Customer Churn Prediction

## Dataset 
🔗 [Customer Churn Dataset](https://docs.google.com/spreadsheets/d/1rnBO9F9xdSUY-WpeOJilMxMRZT-hwwWq6O98OHreY0k/edit?usp=sharing)
It contains the target variable `Churn`, along with a mix of:
- **Numerical features**: `tenure`, `monthly charges`, `total charges`
- **Categorical features**: `gender`, `payment method`, `senior citizen`, and others

## Steps Taken

1. Imported the dataset
2. Cleaned the data by handling missing values and dropping irrelevant columns
3. Performed exploratory data analysis (EDA):
   - Visualized distributions of numerical features using histograms and boxplots
   - Analyzed categorical features using countplots
4. Transformed data by encoding categorical columns
5. Split the dataset into training and test sets
6. Trained and evaluated multiple classification models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
7. Compared model performance using F1 Score and Accuracy
8. Selected **Logistic Regression** for its best overall performance
9. Built a prediction class that takes user inputs and predicts churn outcome

## Results

The Logistic Regression model achieved the best performance among all tested algorithms:  
- **Accuracy**: *80.38%*  
- **F1 Score**: *0.61*

These results indicate the model is reasonably effective in identifying customers who are likely to churn, helping businesses design better retention strategies.
