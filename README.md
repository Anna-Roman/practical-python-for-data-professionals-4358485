# Credit card retention analysis with Python  

This project is based on the LinkedIn Learning course **Practical Python for Data Professionals**. The full course is available from [LinkedIn Learning](https://www.linkedin.com/learning/practical-python-for-data-professionals/introduction?dApp=59033956).  

## Dataset description:  
* This [dataset](https://github.com/Anna-Roman/practical-python-for-data-professionals-4358485/blob/main/data/BankChurners_v2.csv) consists of 10127 customers mentioning their age, salary, marital status, credit card limit etc. There's about 18 features.  
* 16.07% customers have churned.

## Analysis: 
In this project we cleaned the data by checking for duplicates, removing unnecessary columns from our dataset and dealing with missing values.  
Then we explored our data and looked at some statistics like mean, median, min and max.   
Later we took a deeper look at some of our findings, like: customer churn and transaction amount.     

Python code is [here](https://github.com/Anna-Roman/practical-python-for-data-professionals-4358485/blob/main/data/cleaning_data.ipynb)  


###  Findings:
In this [analysis](https://github.com/Anna-Roman/practical-python-for-data-professionals-4358485/blob/main/data/cleaning_data.ipynb) we took a look at the available credin card customer data and tried to understand how to increase customer retention.   

We found that there are No Churned Customers above $11K of Spend.   
![No Churned Customers above $11K](https://github.com/Anna-Roman/practical-python-for-data-professionals-4358485/blob/main/no_churned_customers.png)  

There are no churn customers in the group who have spent more than $11 000. This is interesting and definitely needs further exploration. So, question is 'How can we get more customers above that 11 000 mark?' User surveys for those who are spending above 11 000, and understand why they love this credit card and what keeps them around. If we were also able to get responses from some of the churn customers, we can develop stronger marketing campaigns around our findings.

          


                            

