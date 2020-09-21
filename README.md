# Models for Predicting TELCO Churn

## Project Planning
#### Project Description:
The purpose of this project is to create a model that predicts future Telco customer churn as accuractly as possible, based upon the provided Telco customer dataset. Another primary goal is to identify what drivers to churn are present in the current customer base.

Part of the output from this project will be several files for you to use if you desire to recreate my work, which are: acquire.py, prepare.py, model.py and predictions.csv.

### Short Synopsis of Telco Data:
Project Background:
Customer retention is a key metric for a successful business. The vast majority of new customers are not new telecom customers, and have churned from another company. The costs of acquiring a new customer take time to recoup, and then reducing churn is a key goal for any telecom company.
A good synopsis on churn in the telecom industry can be found here at this [link](http://www.dbmarketing.com/telecom/churnreduction.html#:~:text=Wireless%20companies%20today%20measure%20voluntary,10%20percent%20and%2067%20percent.)

Additional information on the telco dataset and the dataset itself can be accessed [here](https://www.kaggle.com/blastchar/telco-customer-churn) if access to the Codeup database is not available to you.


## Data Dictionary
- churn: If the customer churned = Yes/1; if the customer didn't churn = No/0
- tenure: Number of months person has been a customer
- monthly_charges: Individual customer's monthly charge (in dollars $)
- total_charges: Individual customer's total charges over their entire tenure (in dollars $)
- gender: Female/Male
- is_female: 1 = Yes/female, 0 = No/male
- senior citizen: 0 = No, 1 = Yes
- partner: Yes/No
- dependents: Yes/No
- phone
- 
- 
- 




## Initial Hypotheses and Thoughts

### Thoughts
- The goal of this project is to discover drivers to customer churn, and create models that can accurately predict churn in the future. Thus, the dependent variable in this case will be the rate of churn, or if a customer churned or not. Finding which independent variables (the other datapoints in the dataest) are the most powerful drivers of that churn is what my models will need to focus on. 

- Since the goal of the project is to identify drivers of churn, my positive case will be that a customer churned. Thus, I will want to optimize my model for Recall, in order to minimize as many False Negatives (Type II errors) as possible.

#### Questions to answer:
- 



### Hypotheses

- Is customer churn rate independent of contract type?
    - Null Hypothesis: Churn rate is not significantly impacted by the type of contract a customer has.

- Customers who have an "added service" are significantly less likely to churn than those customers .

- Those who did churn had a significantly different average monthly costs than those who did not churn (on average). [Use T-test, probably a one-tailed test.]

$H_{0}{$: 



## Project Plan:

#### acquire.py
Acquiring the Telco Churn dataset from the Codeup Database.

