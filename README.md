# 🧑‍💼 HR Attrition Prediction using Logistic Regression

📌 Project Overview  
This project focuses on analyzing employee data to predict attrition (whether an employee is likely to leave the company or not). Using Logistic Regression, this HR case study uncovers patterns related to employee turnover and supports HR teams in making data-driven decisions for improving employee retention.

📁 Dataset  
The dataset includes various features related to employee demographics, job profile, and company information:

- **Age**: Employee's age  
- **DistanceFromHome**: Distance between home and workplace  
- **Education**: Education level (1-5)  
- **EmployeeCount**: Count of employees (constant value)  
- **EmployeeID**: Unique identifier for each employee  
- **JobLevel**: Job position level in the company  
- **MonthlyIncome**: Monthly salary of the employee  
- **NumCompaniesWorked**: Total companies the employee has worked for  
- **PercentSalaryHike**: Percentage increase in salary  
- **StandardHours**: Standard working hours (constant value)  
- **StockOptionLevel**: Stock options granted (0-3)  
- **TotalWorkingYears**: Total years of work experience  
- **TrainingTimesLastYear**: Training programs attended in the last year  
- **YearsAtCompany**: Years spent in the current company  
- **YearsSinceLastPromotion**: Years since last promotion  
- **YearsWithCurrManager**: Years with current manager  
- **BusinessTravel**: Frequency of business travel  
- **Department**: Department the employee works in  
- **EducationField**: Field of education  
- **Gender**: Gender of the employee  
- **JobRole**: Job title  
- **MaritalStatus**: Marital status (Single, Married, Divorced)  
- **Over18**: Whether the employee is above 18 (all values are 'Y')  

🛠️ Operations Performed

**Data Loading**  
- Loaded the dataset into a Jupyter Notebook using `pandas`.

**Data Cleaning**  
- Dropped constant columns and unnecessary identifiers  
- Handled missing values and duplicates  
- Encoded categorical variables using label encoding and one-hot encoding

**Exploratory Data Analysis (EDA)**  
- Attrition trends by age, department, income, and job role  
- Relationship between promotions, training, and turnover  
- Correlation heatmaps and distribution plots for key variables  

**Model Building**  
- Applied Logistic Regression for binary classification  
- Split data into training and testing sets  
- Evaluated model using accuracy, precision, recall, F1-score, and confusion matrix  

📊 Key Insights

- Employees with fewer years since last promotion were more likely to stay.  
- High job levels and better salary hikes reduced the likelihood of attrition.  
- Employees who traveled frequently for business showed higher attrition rates.  
- The “Sales Executive” role had comparatively higher turnover.

  📈 Model Performance

- ✅ **Accuracy Achieved**: **83.96%**
- Balanced performance between precision and recall
- Helpful in classifying employee attrition risk for early interventions 

✅ Conclusion  
The logistic regression model identifies key features influencing attrition and can be used to predict potential resignations. With this, HR departments can design focused retention strategies to reduce employee turnover and improve satisfaction.

📈 Future Improvements  

- Include additional behavioral or performance-based features if available  
- Test alternative models such as Random Forest, SVM, or Gradient Boosting  
- Build a dashboard for interactive HR reporting  
- Deploy the model as a web app for real-time attrition prediction  

📦 Tools & Technologies Used  
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  
