# heating-load-prediction-ml
🏠 Heating Load Prediction Using Machine Learning
📌 Overview

This project develops a machine learning model to predict the heating load of buildings based on their physical and architectural characteristics.

🎯 Objective

To model the relationship between building design parameters and energy demand using linear regression.

📊 Dataset

The dataset includes features such as:
Relative Compactness
Surface Area
Overall Height
Glazing Area

The target variable is:

Heating Load

⚙️ Methodology

Data exploration and correlation analysis

Feature selection (removing cooling load to avoid leakage)

Train-test split

Linear regression model

Evaluation using Mean Squared Error (MSE)

📈 Results

Model achieved an MSE of approximately 9

Corresponds to an average prediction error of ~3 units

🔍 Key Insights

Heating and cooling loads are strongly correlated (excluded to avoid leakage)

Relative compactness and height show strong correlation and redundancy

Glazing area appears important but is not uniquely necessary

Multiple features contribute overlapping information

🧠 Conclusion

This project demonstrates how machine learning can model physical systems and highlights the importance of feature correlation and redundancy when interpreting model behavior.
