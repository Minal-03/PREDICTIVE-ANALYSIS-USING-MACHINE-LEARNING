# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MEENAL

*INTERN ID*: CT06DF1241

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

## The objective is to predict the presence or absence of heart disease using a comprehensive dataset containing health-related information from 10,000 individuals. This dataset is designed to support the development of machine learning models that can classify individuals based on their cardiovascular risk profile. By leveraging a diverse range of medical, demographic, and lifestyle features, the goal is to assist in early diagnosis and preventive healthcare strategies.

The dataset comprises various attributes that are known to influence heart health. These include demographic variables such as age and gender, as well as important clinical metrics like systolic and diastolic blood pressure, cholesterol levels (LDL and HDL), and triglyceride concentrations. Additional features include body mass index (BMI), C-reactive protein (CRP) levels, average sleep hours, physical activity habits, smoking status, diabetes status, and family history of heart disease. This rich combination of variables provides a multidimensional view of each individual's health profile, enabling robust predictive modeling.

Before model training, the dataset underwent thorough preprocessing to ensure quality and consistency. All categorical variables (such as gender, smoking status, and diabetes) were numerically encoded, allowing them to be interpreted by machine learning algorithms that require numerical input. For example, gender may be encoded as 0 for male and 1 for female, while smoker status may be represented as binary values indicating yes or no.

An initial exploratory data analysis (EDA) revealed that certain continuous features—particularly age, blood pressure, cholesterol, and sleep hours—contained missing values. These missing entries were addressed using mean imputation, a common and effective technique that replaces missing values with the average value of the respective feature. This approach preserved the overall distribution of the data while ensuring that no rows were dropped due to incomplete records.

After imputation, the dataset was validated for completeness and accuracy. All features were confirmed to be numerically formatted, with no remaining missing values. Outlier detection and basic data cleaning were also performed to remove any anomalies that could negatively impact model performance.

With a clean and structured dataset in place, the next steps include feature selection and the application of classification algorithms such as logistic regression, decision trees, and random forests. The goal is to identify the most important predictors of heart disease and to evaluate model performance using appropriate metrics like accuracy, precision, recall, and F1-score.

In conclusion, this dataset provides a solid foundation for building predictive models aimed at heart disease classification. The combination of clinically relevant features and thorough preprocessing ensures that the data is ready for analysis. The project highlights the potential of data-driven methods in supporting medical decision-making and emphasizes the importance of clean, structured data in health analytics. Through this analysis, we aim not only to predict disease presence but also to uncover valuable insights into the factors that most significantly contribute to cardiovascular health outcomes.
