## Introduction 

This project analyzes customer churn for Databel, a fictitious telecom company, using a dataset provided by DataCamp. 

Utilizing Power BI, I examined key factors influencing customer churn to identify actionable insights for improving customer retention. 
This analysis aims to uncover trends and patterns in customer behavior, helping Databel to develop effective strategies to reduce churn rates and enhance overall customer satisfaction.

## Objective 
1. Analyze the reasons why the customers are churning
2. Provide recommendations to Databel 
____
### What is churn ?

### How to calculate churn rate 

              Churn Rate = [Nb of Churn Customers] /[Nb of Customers]
              
### Calculate the average extra data charges 

              Avg Extra Data Charges = SUM('Databel - Data'[Extra Data Charges]) / CALCULATE([Nb of Customers],'Databel - Data'[Unlimited Data Plan] = "No")

### Calculate the average extra International charges 

              Avg Extra International Charges = SUM('Databel - Data'[Extra International Charges]) / CALCULATE([Nb of Customers],'Databel - Data'[Intl Plan] = "No")
              
### Investigate why customers churn 
    1. Visualize the % churner by reason in which the 2 factors that have the most impact on churn rate come from competitor 
    2. Visualize the churns by churn categories :  Almost half (44.82%)of customers churning are related to the churn category "Competitor"
    3. Create a map to investigate the churn rate by state :  CA is the state that has the highest churn rate of 63.24% 

## 1. Over view 
![alt text](https://github.com/Tsubame88/DataAnalyst_PowerBI_CustomerChurn/blob/main/Screenshot_Overview.png)
1. Present the important KPI : the churn rate across 51 states is quite high at 26.86 %
2. Approximately 45% of the reasons why customers churn is related to the categories "competitor". This rises a question : "is Databell competitive enough ?"
3. Persons with monthly contract tend to churn more than those with yearly contracts
4. The churn rate of people not in a group is significantly higher than that of people in the groups
5. The churn rate in Caliofornia is abnormaly high at 63.24%, we will analyse the Demographic in more detail on the next page

## 2. Demographic analysis
On the next page I will conduct a demographic analysis to understand the impact of age and sex on customer churn.
![alt text](https://github.com/Tsubame88/DataAnalyst_PowerBI_CustomerChurn/blob/main/Screenshot_Demography.png)

### 1. Churn rate by age
   Databel has a wide range of customers from 19-year-olds to 85-year-olds. Within that range, the largest customer group is the 45 to 49-year-olds with 694 persons, followed by 25 to 29-year-olds group with 674 persons. 
  From the 65-year-olds group onward, we can see an increase in the churn rate, which is higher than the average churn rate and tends to increase with age. 
  We need to explore more about the factors that impact churn in this customer group.

### 2. Churn rate by contract categories and gender
  Databel has Month-to-month, One-year and Two-year contracts. The churn rate for people with Monthly contract is significantly high, exceeding 40%, while the churn rate for people with yearly contracts is under 8%. Remember that the average churn rate is approximately 27%. It is clear that there is big difference in churn rate between monthly contract and yearly contract.

### 3. Looking more closely at the contract length, we see an interesting insight: There are month-to-month contracts where the length account is exceed 12 months, even up to more than 24 months. 
Why don't these customers convert to yearly contract ? Let's examine the average monthly charge by contract category, there is very little difference. 

**Therefore I highly recommend that Databel encourage their customers, especially those with Month-to-month contract exceeding 12 months, to switch to yearly contract. This will improve the churn rate.**

       
## 3. Analysis the extra charge 

For those who are not with Unlimited Data Plan and Intl Plan, they have to pay extra charge depend on their data consumption and their international calls. Let's examine the impact of these extra charges on the churn rate.
![alt text](https://github.com/Tsubame88/DataAnalyst_PowerBI_CustomerChurn/blob/main/Screenshot_Extracharge.png)

Databel has Internaltional Plan which is premium plan to International call for free and Unlimited Data Plan which let the customer to have unlimited dowload for free.
For those who are not in these 2 premium plans, have to pay extra charge 
Let's look closely at how extra charge affected on the churn rate

### 1. Churn Rate by the International Plan
  we can see the churn rate for those who are on the International Plan but don't have any international call is significantly high, at over 70%.

  **Recommendation for Databel**: Databel should recommend that these customers back out from the Internaltional Plan if they don't need it as this will help them decrease their monthly charges. This could increase their satisfaction with Databel's customer service and prevent their churn . 

  The churn rate for those who are not on the International Plan but use international call is high, at over 40%, which can be understood as being caused by the high charge fees.
  The average extra international charge is $37.27, but as the chart of churn rate by Extra Internaltional Charges, we can see that there are many customers spend more than $100, even up to $300 or $400, although the number of these customers is not large. 

  More than 5000 customers spend under $20 for the Extra international charge, and the churn rate for this group is 24.77%, lower than the average churn rate of ~ 27%
  For those who spend $20 to $240, the churn rate is high, at over 30%. 

  **Recommendation for Databel**: Databel should recommend that these customers use the Internaltion Plan early after observing their spending over $20, as they have a high demand for it. This will increase their satisfaction with Databel's customer service.   

### 2. Churn rate by extra data charge
  we can see the same situation
  For those who are on the Unlimited Data Plan but use less than 5 GB, the churn rate is high, at nearly 35%.

  **Recommendation for Databel**: Databel should recommend that these customer back out from the Unlimited Plan as they don't need it. This will increase their satisfaction and prevent the churn.

  For those who are not on the Unlimited Data Plan, but use more than 5 GB, have high churn rate, which can be understood as being caused by the high extra data charges, which is over $31 per month, even higher than average monthly charge. 

  **Recommendation for Databel**: Databel should recommend that these customers use the Unlimited Data Plan as they have a high demand for it. 



### 4. Exploring the payment method 
There are 3 types of payments and "Paper check" has the smallest of customers only 371 persons 5.55% of total 









