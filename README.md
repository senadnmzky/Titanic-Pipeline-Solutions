# Titanic-Pipeline-Solutions
Titanic Data Science Pipeline Solutions 


|Variable| Definition | Field values |
|:---|:---| --- |
| survival | Passenger survived     | 0 = No, 1 = Yes |
| pclass   | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex      | Gender          |   |
| Age      | Age in years | |
| sibsp	   | # of siblings/spouses aboard 	| |
| parch	   | # of parents/children aboard 	| |
| ticket   | Ticket number | |
| fare	   | Passenger fare	| |
| cabin	   | Cabin number	| Cabin codes have info about location in the ship |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |
`


📊 **Key Findings:**
- Explored a dataset with 891 observations and 12 variables, identifying patterns and relationships.
- Conducted data cleaning, feature engineering, and extensive exploratory data analysis.
- Discovered intriguing correlations, such as the strong negative correlation between Fare and Pclass, and the impact of gender on survival.

🔄 **Pipeline Methodology:**
In my project, I employed a well-structured pipeline to ensure a systematic and efficient workflow:
**Modeling:** Leveraging various algorithms, including Gradient Boosting, Support Vector Machine, Logistic Regression, Random Forest, and more.
**Feature Importance:** Conducted feature importance analysis to identify the key drivers behind survival predictions.

                  Training Accuracy	Test Accuracy	Best Params
Random Forest	0.886644	0.751196	{'classifier__max_depth': 30, 'classifier__n_e...
Gradient Boosting	0.855219	0.751196	{'classifier__learning_rate': 0.01, 'classifie...
SVM	0.835017	0.751196	{'classifier__C': 10, 'classifier__kernel': 'l...
Logistic Regression	0.835017	0.746411	{'classifier__C': 50}
Perceptron	0.804714	0.736842	{'classifier__max_iter': 100}
KNN	0.857464	0.732057	{'classifier__n_neighbors': 7}
Decision Tree	0.857464	0.729665	{'classifier__max_depth': 5}
Naive Bayes	0.778900	0.705742	{}
SGD	0.785634	0.693780	{'classifier__loss': 'hinge', 'classifier__max...

🔍 **Feature Importance:**
Digging deeper into our models, we unveiled the real stars of the show—the top five factors that significantly influenced survival predictions:
1. "Title1 (Mr.)" – The title "Mr." played a significant role.
2. "Pclass3 (lower socio-economic status)" – Socio-economic status mattered, with lower classes facing greater challenges.
3. "Family Size" – The size of one's traveling family impacted survival rates.
4. "Title5 (Rare)" – Uncommon titles surprisingly influenced outcomes.
5. "Age_Sex_Pclass (AgeSexPclass)" – A combination of age, sex, and passenger class emerged as a crucial predictor.

These findings, coupled with the structured pipeline methodology, shed light on the intricate dynamics of the Titanic tragedy, highlighting the factors that shaped survival. Data science empowers us to extract meaningful insights from historical events, offering valuable lessons for the future.
