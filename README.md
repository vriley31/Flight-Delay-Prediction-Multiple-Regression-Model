# ✈️ Flight Delay Prediction Using Multiple Linear Regression

This project applies **Multiple Linear Regression** techniques in **SAS Studio** to analyze and predict airline arrival delays using operational and environmental factors. The goal is to identify the variables that contribute most to flight delays and demonstrate the application of predictive analytics in the airline industry.

---

## 📋 Project Overview

Airline delays can be influenced by many factors, including weather conditions, staffing availability, fueling time, baggage handling, security procedures, and late-arriving aircraft. This project uses a multiple linear regression model to evaluate these relationships and predict arrival delays.


---

## 🔑 Key Steps

1. Imported the Flight Delay dataset into SAS Studio.
2. Reviewed dataset structure using PROC CONTENTS.
3. Explored the data using descriptive statistics.
4. Evaluated relationships between variables using correlation analysis.
5. Split the data into training and testing datasets.
6. Built a Multiple Linear Regression model using PROC REG.
7. Evaluated model assumptions through residual analysis.
8. Checked for multicollinearity using Variance Inflation Factors (VIF).
9. Assessed model performance and predictor significance.
10. Generated business insights and operational recommendations.

---

## 📸 Project Screenshots

### Dataset Structure (PROC CONTENTS)

<img width="946" height="288" alt="image" src="https://github.com/user-attachments/assets/90d351e1-14e6-4be3-9d9c-22eff81f1303" />


### Descriptive Statistics

<img width="725" height="256" alt="image" src="https://github.com/user-attachments/assets/b77f700b-968a-4560-a218-0216a631a3e8" />


### Fit Diagnostics for Arr_Delay

<img width="975" height="601" alt="image" src="https://github.com/user-attachments/assets/b486a6e6-4d4d-48b9-9b68-7bb0a0f70187" />


### Residual Analysis by Regressors

<img width="975" height="598" alt="image" src="https://github.com/user-attachments/assets/a711fdf0-c4c8-42e5-95ad-ce243be96ddf" />
<img width="971" height="348" alt="image" src="https://github.com/user-attachments/assets/aa3f9d2f-26de-40b0-bd33-cd5e353c9834" />

### Normality Check of Residuals and Distribution
<img width="975" height="526" alt="image" src="https://github.com/user-attachments/assets/867f3ca2-abda-4b56-8feb-9c0bfe629e40" />
<img width="848" height="678" alt="image" src="https://github.com/user-attachments/assets/8427f796-4ff9-41b3-9374-69f8535b643b" />







---

## 🛠️ Technologies Used

- SAS Studio
- SAS PROC IMPORT
- SAS PROC CONTENTS
- SAS PROC MEANS
- SAS PROC CORR
- SAS PROC SURVEYSELECT
- SAS PROC REG
- SAS PROC SGPLOT
- SAS PROC UNIVARIATE

---

## 📊 Model Variables

### Target Variable
- Arr_Delay (Arrival Delay)

### Predictor Variables
- Airport_Distance
- Number_of_flights
- Weather
- Support_Crew_Available
- Baggage_loading_time
- Late_Arrival_o
- Cleaning_o
- Fueling_o
- Security_o

---

## 📈 Business Insights

The regression model provides valuable insight into the operational factors that contribute to airline delays. By identifying the strongest predictors, airlines can:

- Improve scheduling efficiency.
- Reduce turnaround times.
- Allocate support crews more effectively.
- Improve customer satisfaction through better delay management.
- Use predictive analytics to proactively address delay risks.

---

## 📚 Learning Outcomes

Through this project, I gained experience with:

- Data preparation and exploration in SAS.
- Train-test data splitting techniques.
- Multiple Linear Regression modeling.
- Model diagnostics and assumption testing.
- Interpretation of regression coefficients and statistical significance.
- Translating analytical findings into business recommendations.

---

## 📖 References

Gupta, D. (2018). *Applied analytics through case studies using SAS and R: Implementing predictive models and machine learning techniques*. Apress.

Gupta, D. (2018). *Source code for applied analytics through case studies using SAS and R*. GitHub.

---

## 👤 Author

**Victoria Riley**

Graduate Student | Data Analytics & Predictive Modeling

GitHub: [@vriley31](https://github.com/vriley31)
