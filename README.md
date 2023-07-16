# predicting_student_performance
This project aims to predict the performance of students based on their game play data. It utilizes machine learning techniques to train a model that can predict the correctness of students' responses to various questions.

Introduction:
The project focuses on predicting student performance based on game play data. It utilizes a machine learning algorithm called XGBoost to train a model that can predict the correctness of students' responses to different questions. The project aims to provide insights into student learning patterns and potentially identify areas where additional support may be needed.

Requirements:
The following dependencies are required to run the project:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. plotly
6. scikit-learn
7. xgboost

Installation:
1. Clone the repository:
git clone https://github.com/harshil2201/student-performance-prediction.git

2. Navigate to the project directory:
cd student-performance-prediction

3. Install the required libraries:
pip install -r requirements.txt

Feature Engineering:
The feature engineering process involves creating new features based on the existing data to improve the model's predictive performance. It includes creating dummy variables, aggregating statistics, and grouping the data based on specific criteria.

Train XGBoost Model:
The XGBoost model is trained using the training data. It utilizes the XGBoostClassifier from the XGBoost library with specified hyperparameters. The training process includes cross-validation using the GroupKFold strategy to account for group-wise splitting.

Infer Test Data:
The trained model is used to make predictions on the test data. The test data is preprocessed using the same feature engineering steps as the training data. The model predicts the correctness of the students' responses to each question, and the results are saved in a submission file.

EDA submission.csv
The submission.csv file contains the predictions made by the model on the test data. This section performs exploratory data analysis (EDA) on the submission file to provide insights into the model's performance.

Feel free to customize the README file based on your project's specific details and requirements. Provide instructions for installation, usage, and any additional information or notes that may be relevant.
