# Employee_Attrition

In this Project, I use dataset from https://www.kaggle.com/datasets/thedevastator/employee-attrition-and-factors 
And try to deep diving what factors that push Employee to do Attrition in the Company and how to minimize the Attrition, Especially for Employee that have High Job Level

Data Understanding :
This Dataset Contains 35 Columns :
- Age	: The age of the employee. (Numerical)
- Attrition	: Whether or not the employee has left the organization. (Categorical) << **Our Target**
- BusinessTravel	: The frequency of business travel for the employee. (Categorical)
- DailyRate	: The daily rate of pay for the employee. (Numerical)
- Department	: The department the employee works in. (Categorical)
- DistanceFromHome	: The distance from home in miles for the employee. (Numerical)
- Education	: The level of education achieved by the employee. (Categorical)
- EducationField	: The field of study for the employee's education. (Categorical)
- EmployeeCount	: The total number of employees in the organization. (Numerical)
- EmployeeNumber	: A unique identifier for each employee profile. (Numerical)
- EnvironmentSatisfaction	: The employee's satisfaction with their work environment. (Categorical)
- Gender :	The gender of the employee. (Categorical)
- HourlyRate	: The hourly rate of pay for the employee. (Numerical)
- JobInvolvement	: The level of involvement required for the employee's job. (Categorical)
- JobLevel	: The job level of the employee. (Categorical)
- JobRole	: The role of the employee in the organization. (Categorical)
- JobSatisfaction	: The employee's satisfaction with their job. (Categorical)
- MaritalStatus	: The marital status of the employee. (Categorical)
- MonthlyIncome	: The monthly income of the employee. (Numerical)
- MonthlyRate	: The monthly rate of pay for the employee. (Numerical)
- NumCompaniesWorked	: The number of companies the employee has worked for. (Numerical)
- Over18	: Whether or not the employee is over 18. (Categorical)
- OverTime	: Whether or not the employee works overtime. (Categorical)
- PercentSalaryHike	: The percentage of salary hike for the employee. (Numerical)
- PerformanceRating	: The performance rating of the employee. (Categorical)
- RelationshipSatisfaction	: The employee's satisfaction with their relationships. (Categorical)
- StandardHours	: The standard hours of work for the employee. (Numerical)
- StockOptionLevel	: The stock option level of the employee. (Numerical)
- TotalWorkingYears :	The total number of years the employee has worked. (Numerical)
- TrainingTimesLastYear	: The number of times the employee was taken for training in the last year. (Numerical)
- WorkLifeBalance	: The employee's perception of their work-life balance. (Categorical)
- YearsAtCompany	: The number of years the employee has been with the company. (Numerical)
- YearsInCurrentRole	: The number of years the employee has been in their current role. (Numerical)
- YearsSinceLastPromotion	: The number of years since the employee's last promotion. (Numerical)
- YearsWithCurrManager	: The number of years the employee has been with their current manager. (Numerical)

We don't use all this Column / Features to Analyze this Dataset, Instead we use Features that have highest Correlation with our target ['Attrition'] for better approach.

**Note**

Because Library Plotly.Express need Improvement for their Compatibility with Github, some Image produced by Plotly might be small / error
you can look at the better Plotly Version in here : [Better Version](http://bit.ly/3IIEGMh).

# Modeling
This dataset is Imbalance Classification Dataset
I use Oversampling with SMOTE with RandomForest Classifier and Accuracy as the key metrics

For more information, please look after my notebook in this Github
Thanks
