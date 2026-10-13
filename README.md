# Customer Churn Prediction Using Machine Learning

## Overview
This project predicts customer churn using machine learning techniques. It analyzes customer data, identifies churn patterns, and compares multiple classification algorithms to predict whether a customer is likely to leave a service.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## Machine Learning Algorithms
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Dataset
The dataset contains 100 customer records and 11 columns, including customer demographics, tenure, contract type, monthly charges, and churn status.

- Total customers: 100
- Customers who stayed: 63
- Customers who churned: 37
- Missing values: 0
- Duplicate rows: 0

## Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Data visualization
5. Training and testing data split
6. Machine learning model training
7. Model evaluation using accuracy, precision, recall, and F1-score
8. Confusion matrix visualization
9. Feature importance analysis
10. Sample customer churn prediction

## Results
The project compares the performance of three machine learning models and generates visualizations to understand customer churn patterns. Actual evaluation metrics are produced by running the notebook.

## How to Run
1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Install the required libraries:

   ```bash
   python -m pip install pandas numpy matplotlib scikit-learn jupyter
   ```

4. Open `Customer_Churn_Prediction.ipynb`.
5. Ensure the dataset CSV file is in the same folder.
6. Select a Python kernel and run the notebook cells in order.

## Future Enhancements
- Use a larger real-world dataset.
- Improve model performance through hyperparameter tuning.
- Develop a web interface for customer churn prediction.
- Deploy the model as a web application.

## Conclusion
This project demonstrates the application of machine learning to customer churn analysis and prediction, providing practical experience in data preprocessing, visualization, classification, and model evaluation.

**Note:** This is an educational project using a small dataset of 100 customer records. Its results should not be treated as a reliable measure of real-world performance.
