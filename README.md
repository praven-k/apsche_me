# burnoutanalysis
Overview

COVID 19 pandemic has bought never though and un-imagined situation for whole world. While it has impacted all sectors of work , IT sector employees or white-collar employees are the ones who are least impacted in terms of delivering the expected outcomes. Instead, many articles and comments on LinkedIn suggested that WFH has resulted in increased productivity for an organization. Many complained about burn-out and mental stress blaming WFH for leaving no boundaries in their personal and job life. We will analyze the openly 
available data from Kaggle which is a fractional sample which definitely does not represent the world.

Expected outcome

 Analyze the available data to answer stats from the data
 
 Conclusions
 
Here is the list of few conclusions made based on the data. I am publishing it first to put up insights at the top.-

10 % of total employees are extremely burned out

29 % of total employees are moderately burned out

54 % of total employees are slightly burned out

Only 1 % of total employees are not burned out

Managers of bigger teams are more burned out compared to managers of smaller teams — Employees having more bigger team (more people reporting to them) are more burned
out compared to employees with lesser number of people reporting them

Overall, Males are more burned out compared to females as majority of females are slightly burned-out while majority of males are moderately and 
extremely burned-out
What data do we have ?

Employee ID: The unique ID allocated for each employee (example: fffe390032003000)

Date of Joining: The date-time when the employee has joined the organization (example: 2008–12–30)

Gender: The gender of the employee (Male/Female)

Company Type: The type of company where the employee is working (Service/Product)

WFH Setup Available: Is the work from home facility available for the employee (Yes/No)

Designation: The designation of the employee of work in the organization. In the range of [0.0, 5.0] bigger is higher designation.

Resource Allocation: The amount of resource allocated to the employee to work, i.e. number of working hours. In the range of [1.0, 10.0] (higher means more resource)

Mental Fatigue Score: The level of fatigue mentally the employee is facing. In the range of [0.0, 10.0] where 0.0 means no fatigue and 10.0 means completely fatigue.

Burn Rate: The value we need to predict for each employee telling the rate of Bur out while working. In the range of [0.0, 1.0] where the higher the value is more is the burn out.


59 % of males and 41 % percent of females are extremely burned out which concludes that males are more burned out compared to females

Employees working in a Service based company are more Burned-out compared to an employee working in a Product based company

Major steps

Setup development environment — Google Colab, Python libraries

Download data using opendatasets library developed by Jovian

Perform visualizations on the training data and get some stats displayed

Build a model and predict
