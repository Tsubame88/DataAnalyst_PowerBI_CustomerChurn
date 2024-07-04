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

### Investigate why customers churn 
    1. Visualize the % churner by reason in which the 2 factors that have the most impact on churn rate come from competitor 
    2. Visualize the churns by churn categories :  Almost half (44.82%)of customers churning are related to the churn category "Competitor"
    3. Create a map to investigate the churn rate by state :  CA is the state that has the highest churn rate of 63.24% 

### 1.Over view 
![alt text](https://github.com/Tsubame88/DataAnalyst_PowerBI_CustomerChurn/blob/main/Screenshot_Overview.png)
1. Present the important KPI : the churn rate across 51 states is quite high at 26.86 %
2. Approximately 45% of the reasons why customers churn is related to the categories "competitor". This rises a question : "is Databell competitive enough ?"
3. Persons with monthly contract tend to churn more than those with yearly contracts
4. The churn rate of people not in a group is significantly higher than that of people in the groups
5. The churn rate in Caliofornia is abnormaly high at 63.24%, we will analyse the Demographic in more detail on the next page

### 2.Demographic analysis
On the next page I will conduct a demographic analysis to understand the impact of age and sex on customer churn.
![alt text](https://github.com/Tsubame88/DataAnalyst_PowerBI_CustomerChurn/blob/main/Screenshot_Demography.png)

1. Churn rate by age
   Databel has a wide range of customers from 19-year-olds to 85-year-olds. Within that range, the largest customer group is the 45 to 49-year-olds with 694 persons, followed by 25 to 29-year-olds group with 674 persons. 
From the 65-year-olds group onward, we can see an increase in the churn rate, which is higher than the average churn rate and tends to increase with age. 
We need to explore more about the factors that impact churn in this customer group.

2. Churn rate by contract categories and gender
Databel has Month-to-month, One-year and Two-year contracts. The churn rate for people with Monthly contract is significantly high, exceeding 40%, while the churn rate for people with yearly contracts is under 8%. Remember that the average churn rate is approximately 27%. It is clear that there is big difference in churn rate between monthly contract and yearly contract.

Looking more closely at the contract length, we see an interesting insight: There are month-to-month contracts where the length account is exceed 12 months, even up to more than 24 months. 
Why don't these customers convert to yearly contract ? Let's examine the average monthly charge by contract category, there is very little difference. 

**Therefore I highly recommend that Databel encourage their customers, especially those with Month-to-month contract exceeding 12 months, to switch to yearly contract. This will improve the churn rate.**

       
### Inspecting group 
The Databell offers group contract to customers from the same household. The advantage of the customer is discounted rate while its a great way for Databel to grow its customer base.
Analyse if the customers who are part of group have a lower phone bill and if it impacted on the churn rate.
The groups from 2 persons have significantly lower average monthly charge than the person not in group contract.

### Inspecting the contract type 
There are many kind of contract "One Year" "Two Year" "Month-to-Month". WE can gather "One Year" contract and "Two Year" contract into one. By this way we can observe the different between yearly contract and monthly contract .
+ The persons who are in monthly contract have hight churn rate of 46.29%
+ The person who are in yearly contract have low churn rate of 6.62%

**Recommand to Databel**: to stop customer from churning we can propose them to use yearly contract.

### Exploring the payment method 
There are 3 types of payments and "Paper check" has the smallest of customers only 371 persons 5.55% of total 

### Inspecting the Unlimited Data Plan 

    **Unlimited Data Plan** : Indicate if the customer has free unlimited download capacity with "Yes" or "NO". This premium is reflected in the amount of monthly charge.

It appears that customers who are on unlimited plan are more likely to churn 32.11% compare to 16.10% of those who are not .

Let's see if it is related to a certain amount of mobile data(GB) being used 

CHurn rate for people on an unlimited plan who consume less than 5 GB of data is 34.71%.
Its quite high. 
**Recommand to Databal** : Contact customers who are on Unlimited Plan but use less than 5G and propose them to downgrade their plan. This will increase customers satisfaction and stop customer from churning.

### Inspecting International call 
Databel curious about the behavior of customers who call internationally and if paying for an international plan influences their loyalty 

**Intl Plan**: indicates if the customer has a premium plan to call internationally for free with "yes" or "no". This premium is reflected in the amount of monthly charge. 

Focus on the state that has the highest churn rate California, We can see that the churn rate of persons who actived international call but dont have Intl Plan is 72 %. These person can be potential clients for the new promotion of the Intl Plan. 

Also, I discoverd that in general, the churn rate for customers who have Intl Plan but dont but don't active the call is sky-high of 71.19 %.

**Recommand to Databel**: Contact customers who are on Intl Plan but dont have international call and propose they to downgrade their plan. This will increase customer satisfaction and stop customer from churning.
For California, navigate the promotion of Intl Plan to the customers churned and already active International call.




