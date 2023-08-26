# Employee attrition ~ a prescriptive modelling
![resignation](https://github.com/franciskyalo/employee_attrition/assets/94622826/df77e401-b01b-4804-a25c-bec5246dfae4)

### Overview 

Employee attrition is a critical concern in today's business landscape, with significant implications for organizations worldwide. High attrition rates result in increased costs, reduced productivity, and diminished morale. To address this issue, you must understand the underlying factors driving attrition and develop effective retention strategies. This capstone project focuses on analyzing the Employee Attrition dataset for a tech company, which provides comprehensive information on employee demographics, job roles, satisfaction levels, compensation, and work-life balance.

### Business understanding

Recruiting, hiring, and training new employees entail substantial costs, compounded by the loss of institutional knowledge. Attrition also disrupts productivity and hampers organizational growth, affecting economic performance at micro and macro levels. By exploring the factors contributing to attrition and developing effective retention strategies, this project contributes to the formulation of robust economic and fiscal policies that foster stability, productivity, and sustainable growth within the business sector.

#### Main objective 

The main objective of the project is to come up with a **prescriptive model** that would be able to identify which factors contribute the most to an employee attritioning giving Human resources department the chance to intervene and also improve on some of the policies to ensure that employees are happy.


### Data understanding 

Data had 1470 records and 35 columns containing different information on an employee such as their age, marital status, education level, job satisfaction etc.


### Modelling 

Modelling will involve two distinct steps:

- creating a logistic regression model using `statsmodels` so as to make use of statsmodels `model summary` functionality that prints out the models coefficients and p-values to determine the log-likehood of feature in determining if an employee or not

- creating a logistic regression model using `scikit-learn` for deployment into a production enviroment. Tuning will also be done to ensure the best parameters for the model are used to guarantee good accuracy

### Recommendations 

- Departments like "Research & Development" and "Sales" appear to have higher attrition rates. It's important to delve into the **specific work conditions, growth opportunities, and job satisfaction levels** within these departments. Address any issues that might be leading to dissatisfaction and explore ways to enhance employee engagement and career growth.

- Special attention should be given to employees holding job roles such as **"Sales Executive" and "Sales Representative**." Identify the unique challenges they might be facing and provide targeted support, training, and resources to improve their job satisfaction and retention.

- The model indicates that employees working overtime have a higher likelihood of quitting. This could **suggest burnout or work-life balance issues**. Evaluate the **necessity of overtime work, streamline processes, and implement strategies to ensure employees are not consistently overburdened**. Promote a healthy work-life balance to prevent burnout and maintain job satisfaction.

- The result highlighting **"MaritalStatus_Single" as a factor suggests that single employees might be more prone to attrition**. Consider offering additional support to single employees, such as **mentorship programs, social activities, or wellness initiatives**. Encouraging a sense of belonging and community can make a positive impact on their job satisfaction and commitment.
- 
