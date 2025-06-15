Titanic Survival Prediction
This repository contains a machine learning project focused on predicting the survival of passengers on the Titanic using the famous Kaggle Titanic dataset. The project explores data analysis, visualization, preprocessing, and classification modeling.
Project Structure
.
├── Titanic.ipynb          # Final Jupyter notebook with full EDA and model
├── Titanic (1).ipynb      # Alternate notebook (possibly intermediate)
├── Titanic Project.ipynb  # Initial/alternative project version
├── train.csv              # Training dataset
├── test.csv               # Test dataset
└── README.md              # Project documentation
Objective
The objective is to build a predictive model that answers the question: "What sorts of people were more likely to survive?" using passenger data such as age, gender, class, etc.
Techniques Used

Exploratory Data Analysis (EDA) with pandas and seaborn
Data Cleaning and Feature Engineering
Model Training and Evaluation
Logistic Regression, Decision Trees, Random Forest
Hyperparameter tuning

Highlights

Missing values handled thoughtfully (e.g., imputation strategies)
Categorical variables encoded using Label Encoding and One-Hot Encoding
Comparison of multiple models using accuracy and confusion matrix
Clear visualizations showing survival patterns

Results

Best Accuracy Achieved: ~[Insert your best score here]% on validation set
Final Model Used: [e.g., Random Forest / Logistic Regression]

Requirements
To run the notebooks, you'll need:
bash
pip install pandas numpy matplotlib seaborn scikit-learn
How to Run
Clone the repository:
bash
git clone https://github.com/Arpit2744/titanic-survival-prediction.gitcd titanic-survival-prediction


Open Titanic.ipynb in Jupyter Notebook or VS Code
Run all cells to see data analysis and model predictions

Dataset Description
train.csv: Contains the labeled data (features + survival labels)
test.csv: Contains the unlabeled data used for final predictions

References

Kaggle Titanic Competition
Scikit-learn documentation
Python for Data Analysis by Wes McKinney

Contact
If you have any questions, feel free to reach out via GitHub Issues.

