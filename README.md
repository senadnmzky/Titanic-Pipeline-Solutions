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

🔍 **Feature Importance:**
Digging deeper into our models, we unveiled the real stars of the show—the top five factors that significantly influenced survival predictions:
1. "Title1 (Mr.)" – The title "Mr." played a significant role.
2. "Pclass3 (lower socio-economic status)" – Socio-economic status mattered, with lower classes facing greater challenges.
3. "Family Size" – The size of one's traveling family impacted survival rates.
4. "Title5 (Rare)" – Uncommon titles surprisingly influenced outcomes.
5. "Age_Sex_Pclass (AgeSexPclass)" – A combination of age, sex, and passenger class emerged as a crucial predictor.

These findings, coupled with the structured pipeline methodology, shed light on the intricate dynamics of the Titanic tragedy, highlighting the factors that shaped survival. Data science empowers us to extract meaningful insights from historical events, offering valuable lessons for the future.
